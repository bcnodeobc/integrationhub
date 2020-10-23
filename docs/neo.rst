========
NEO
========

This project using javascript to testing the rpc.

User can test the rpc by using Postman nodejs - request.

- Be awesome
- Make things faster

getblockcount
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblockcount

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    {
        
    } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblockcount',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
     body: JSON.stringify({})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the current block timeout::

    {
    "status": 200,
    "values": 6332829
    }  

getaccountstate
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getaccountstate

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

  address       {
                "address": "AJBENSwajTzQtwyJFkiJSv7MAaaMc7DsRz"
                }

Example
--------
example::

    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getaccountstate',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"address":"AJBENSwajTzQtwyJFkiJSv7MAaaMc7DsRz"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the current block timeout::

    {
    "status": 200,
    "values": {
        "version": 0,
        "script_hash": "0x1179716da2e9523d153a35fb3ad10c561b1e5b1a",
        "frozen": false,
        "votes": [],
        "balances": []
        }
    }  

getassetstate
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getassetstate

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    asset id    {
                "asset_id": "c56f33fc6ecfcd0c225c4ab356fee59390af8560be0e930faebe74a6daff7c9b"
                } 

Example
--------
example::

    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getassetstate',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"asset_id":"c56f33fc6ecfcd0c225c4ab356fee59390af8560be0e930faebe74a6daff7c9b"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the current block timeout::

    {
    "status": 200,
    "values": {
        "version": 0,
        "id": "0xc56f33fc6ecfcd0c225c4ab356fee59390af8560be0e930faebe74a6daff7c9b",
        "type": "GoverningToken",
        "name": [
            {
                "lang": "zh-CN",
                "name": "小蚁股"
            },
            {
                "lang": "en",
                "name": "AntShare"
            }
        ],
        "amount": "100000000",
        "available": "100000000",
        "precision": 0,
        "owner": "00",
        "admin": "Abf2qMs1pzQb8kYk9RuxtUb9jtRKJVuBJt",
        "issuer": "Abf2qMs1pzQb8kYk9RuxtUb9jtRKJVuBJt",
        "expiration": 4000000,
        "frozen": false
        }
    } 

getbestblockhash
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getbestblockhash

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    {
        
    } 

Example
--------
example::

    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getbestblockhash',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the current block timeout::

    {
    "status": 200,
    "values": "0xe8b139163776e5ac21336052e20b30933ff84f9cad9121a36f7d1447a058bba3"
    }  

getblockbyhash
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblockbyhash

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    hash        {
    verbose     "hash": "773dd2dae4a9c9275290f89b56e67d7363ea4826dfd4fc13cc01cf73a44b0d0e",
                "verbose": "1" 
                } 

Example
--------
example::

    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblockbyhash',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"hash":"773dd2dae4a9c9275290f89b56e67d7363ea4826dfd4fc13cc01cf73a44b0d0e","verbose":"1"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the current block timeout::

    {
    "status": 200,
    "values": "000000002deadfa82cbc4682f5800ec72a8d8bd6afa469af5b2de83a51d28795a893222816f8081bf1054136cca420f807f844a958b2dea482dfc99d2538ef9c77d13320f9263659d4220f00878f40bd841c552a59e75d652b5d3827bf04c165bbe9ef95cca4bf5501fd450140b514d8562ad3badac0e097a502a43c58e23c75029dad8ccdb3b1ce221067d73d5612950e38c7565d6b166ef62894399a6f152c38a1bdb8c7d3715f75f20c1c734053de02d5779551a692d8b50f3a30a81fcf88c8a06bd733b192cbbe42b21611903287fa00a7847e17b4b319331bd7c52407f40ac1a109b48d91da55aa8632e1db40e443f55108c5eefd99f954e06b21e97a4f0cf64dbd4e52426c27f7046cd880d6a7b1a507131c39afa48b9cac16411d6f84ec2f0b5d9977e5f1e3ce760a127b31409b8a52714b37a3b0970a19b4fb2669d2aa41ea85e05e68dfb03a197d505282dd53846ca58b1457504c65759a9ceb8f84f5148dec71727e9c743e986092728174409dfcbda69cef1164936212e8e5d91965c8a976dc8dbcb5ea7d2f2d2f0105dadb902924559fede016a1f76a2c7ab0ff89a6446b0c19c88375906c8b9eccb61bc1f1552102486fd15702c4490a26703112a5cc1d0923fd697a33406bd5a1c00e0013b09a7021024c7b7fb6c310fccf1ba33b082519d82964ea93868d676662d4a59ad548df0e7d2102aaec38470f6aad0042c6e877cfd8087d2676b0f516fddd362801b9bd3936399e2103b209fd4f53a7170ea4444e0cb0a6bb6a53c2bd016926989cf85f9b0fba17a70c2103b8d9d5771d8f513aa0869b9cc8d50986403b78c6da36890638c3d46a5adce04a2102ca0e27697b9c248f6f16e085fd0061e26f44da85b58ee835c110caa5ec3ba5542102df48f60e8f3e01c48ff40b9b7f1310d7a8b2a193188befe1c2e3df740e89509357ae010000878f40bd00000000"
    }  

getblockbyindex
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblockbyindex

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    index       {
    verbose     "index": "10000",
                "verbose": "1",
                } 

Example
--------
example::

    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblockbyindex',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"index":"10000","verbose":"1"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the current block timeout::

    {
    "status": 200,
    "values": 
    }  
