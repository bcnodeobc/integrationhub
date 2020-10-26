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

Api for this rpc::

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
Returns the status::

    {
    "status": 200,
    "values": 6332829
    }  

getaccountstate
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

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
Returns the status::

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

Api for this rpc::

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
Returns the status::

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

Api for this rpc::

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
Returns the status::

    {
    "status": 200,
    "values": "0xe8b139163776e5ac21336052e20b30933ff84f9cad9121a36f7d1447a058bba3"
    }  

getblockbyhash
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

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
Returns the status::

    {
    "status": 200,
    "values": "000000002deadfa82cbc4682f5800ec72a8d8bd6afa469af5b2de83a51d28795a893222816f8081bf1054136cca420f807f844a958b2dea482dfc99d2538ef9c77d13320f9263659d4220f00878f40bd841c552a59e75d652b5d3827bf04c165bbe9ef95cca4bf5501fd450140b514d8562ad3badac0e097a502a43c58e23c75029dad8ccdb3b1ce221067d73d5612950e38c7565d6b166ef62894399a6f152c38a1bdb8c7d3715f75f20c1c734053de02d5779551a692d8b50f3a30a81fcf88c8a06bd733b192cbbe42b21611903287fa00a7847e17b4b319331bd7c52407f40ac1a109b48d91da55aa8632e1db40e443f55108c5eefd99f954e06b21e97a4f0cf64dbd4e52426c27f7046cd880d6a7b1a507131c39afa48b9cac16411d6f84ec2f0b5d9977e5f1e3ce760a127b31409b8a52714b37a3b0970a19b4fb2669d2aa41ea85e05e68dfb03a197d505282dd53846ca58b1457504c65759a9ceb8f84f5148dec71727e9c743e986092728174409dfcbda69cef1164936212e8e5d91965c8a976dc8dbcb5ea7d2f2d2f0105dadb902924559fede016a1f76a2c7ab0ff89a6446b0c19c88375906c8b9eccb61bc1f1552102486fd15702c4490a26703112a5cc1d0923fd697a33406bd5a1c00e0013b09a7021024c7b7fb6c310fccf1ba33b082519d82964ea93868d676662d4a59ad548df0e7d2102aaec38470f6aad0042c6e877cfd8087d2676b0f516fddd362801b9bd3936399e2103b209fd4f53a7170ea4444e0cb0a6bb6a53c2bd016926989cf85f9b0fba17a70c2103b8d9d5771d8f513aa0869b9cc8d50986403b78c6da36890638c3d46a5adce04a2102ca0e27697b9c248f6f16e085fd0061e26f44da85b58ee835c110caa5ec3ba5542102df48f60e8f3e01c48ff40b9b7f1310d7a8b2a193188befe1c2e3df740e89509357ae010000878f40bd00000000"
    }  

getblockbyindex
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

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
Returns the status::

    {
    "status": 200,
    "values": 
    }  

getblockheader
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblockheader

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    hash        {
    verbose     "hash": "a5508c9b6ed0fc09a531a62bc0b3efcb6b8a9250abaf72ab8e9591294c1f6957",
                "verbose": "1"
                } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblockheader',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"hash":"a5508c9b6ed0fc09a531a62bc0b3efcb6b8a9250abaf72ab8e9591294c1f6957","verbose":"1"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": "00000000e5abdddd1bb06ac4530a0cb699a99453fc64086708659cac9a8258061ab533698e6a6e91a592649a7fb0af5afa4d899d871819994fd260dc6b50c1be2badff0974486c5b40ac27006d80cbea5b752a7683f5011bdaaccee8c4d2555c829fa51e31551ef201fd45014047c4915575949baa8594877105598df8f06875539aa98e2b028ebf5b4f17122831d32308142062db8b50e1bbe07d2313510c0ae289e7f9a97b20cbe858e62ba2407187c52864ececa40ad3c76f221c7ef9918b9e2dd058156021a88737ca0a54722482297c9775af35d52cd4e01648a34662748d00f5b3c63ac2ae346b6bebf236401f23118e86ce3a74ae1bd92c41675f7f8dc94a6ceb2796a2a3741d248f0d5f07aaeda7ec47287317926382d921a47a38bb5793ebef91cbff7a04313d91a4d3ea403aecb64ecde98fc705dd4e9e26580fbeaf27bd24b69507b1b7d348ec29f7bc09948d237d7ca6fb3b253b59297bdc7fe10d1132fef3ac0d728e5063baebbc99cd4053871e5b4138d5b3dfcf79264d240b389417213517ad1fff9636d067a32d288b660503695c4341ce0799d0d9b1e78a62322f10eef1f44f3dd9ec4d311381a3daf15521024c7b7fb6c310fccf1ba33b082519d82964ea93868d676662d4a59ad548df0e7d21025bdf3f181f53e9696227843950deb72dcd374ded17c057159513c3d0abe20b642102aaec38470f6aad0042c6e877cfd8087d2676b0f516fddd362801b9bd3936399e2103b209fd4f53a7170ea4444e0cb0a6bb6a53c2bd016926989cf85f9b0fba17a70c2103b8d9d5771d8f513aa0869b9cc8d50986403b78c6da36890638c3d46a5adce04a2102ca0e27697b9c248f6f16e085fd0061e26f44da85b58ee835c110caa5ec3ba5542102df48f60e8f3e01c48ff40b9b7f1310d7a8b2a193188befe1c2e3df740e89509357ae00"
    }  

getblockhash
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblockhash

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    index       {
                "index": "10000" 
                } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblockhash',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"index":"10000"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": "0x4c1e879872344349067c3b1a30781eeb4f9040d3795db7922f513f6f9660b9b2"
    }  

getblocksysfee
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblocksysfee

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    index       {
                "index": "1005434" 
                } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getblocksysfee',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"index":"1005434"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": "195500"
    }  

getclaimable
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getclaimable

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    address     {
                "address": "AGofsxAUDwt52KjaB664GYsqVAkULYvKNt" 
                } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getclaimable',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"address":"AGofsxAUDwt52KjaB664GYsqVAkULYvKNt"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": 
    }  

getconnectioncount
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getconnectioncount

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getconnectioncount',
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
Returns the status::

    {
    "status": 200,
    "values": 10
    }  

getcontractstate
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for call the rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getcontractstate

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    script hash          
                    {
                    "script_hash": "dc675afc61a7c0f7b3d2682bf6e1d8ed865a0e5f"
                    } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getcontractstate',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"script_hash":"dc675afc61a7c0f7b3d2682bf6e1d8ed865a0e5f"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": 
    }  

getmetricblocktimestamp
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getmetricblocktimestamp

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    blocks number       
    end height          {
                        "blocksNumber": "10",
                        "endHeight": "460000" 
                        } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getmetricblocktimestamp',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"blocksNumber":"10","endHeight":"460000"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": 
    }  

getnep5balances
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getnep5balances

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    address     
                {
                "address": "1aada0032aba1ef6d1f07bbd8bec1d85f5380fb3" 
                } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getnep5balances',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"address":"1aada0032aba1ef6d1f07bbd8bec1d85f5380fb3"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": 
    }  

getnep5transfers
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getnep5transfers

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    address                 
    timestamps Start        {
    timestamps End          "address": "AbHgdBaWEnHkCiLtDZXjhvhaAK2cwFh5pF",
                            "timestampsStart": "1553105830",
                            "timestampsEnd": "1557305830" 
                            } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getnep5transfers',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"address":"AbHgdBaWEnHkCiLtDZXjhvhaAK2cwFh5pF","timestampsStart":"1553105830","timestampsEnd":"1557305830"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": 
    }  

getstorage
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getstorage

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    script hash       
    key                 {
                        "script_hash": "03febccf81ac85e3d795bc5cbd4e84e907812aa3",
                        "key": "5065746572" 
                        } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getstorage',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"script_hash":"03febccf81ac85e3d795bc5cbd4e84e907812aa3","key":"5065746572"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": 
    }  

gettransactionheight
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/gettransactionheight

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    transaction id      
                        {
                        "txid": "9ae1fd32d525eff2a1bb1fc8d0cd2cfb4cc97a06a232bb87fc58e4fe3bc2a845"
                        } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/gettransactionheight',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"txid":"9ae1fd32d525eff2a1bb1fc8d0cd2cfb4cc97a06a232bb87fc58e4fe3bc2a845"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": 
    }  

gettxout
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/gettxout

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    transaction id       
                        {
                        "txid": "9ae1fd32d525eff2a1bb1fc8d0cd2cfb4cc97a06a232bb87fc58e4fe3bc2a845"
                        } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/gettxout',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"txid":"9ae1fd32d525eff2a1bb1fc8d0cd2cfb4cc97a06a232bb87fc58e4fe3bc2a845"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": 
    }  

getpeers
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getpeers

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getpeers',
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
Returns the status::

    {
    "status": 200,
    "values": {
        "unconnected": [
            {
                "address": "54.65.179.69",
                "port": 10333
            },
            {
                "address": "18.140.231.98",
                "port": 10333
            },
            {
                "address": "142.0.199.100",
                "port": 10333
            },
            {
                "address": "46.4.15.97",
                "port": 20037
            },
        ],
        "bad": [],
        "connected": [
            {
                "address": "183.129.226.75",
                "port": 10333
            },
            {
                "address": "13.89.56.95",
                "port": 10333
            },
            {
                "address": "8.210.66.154",
                "port": 10333
            }
        ]
    }
    } 

getunclaimed
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getunclaimed

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    address      
                        {
                        "address": "AGofsxAUDwt52KjaB664GYsqVAkULYvKNt"
                        } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getunclaimed',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"address":"AGofsxAUDwt52KjaB664GYsqVAkULYvKNt"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": 
    }  

getvalidators
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getvalidators

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getvalidators',
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
Returns the status::

    {
    "status": 200,
    "values": [
        {
            "publickey": "02486fd15702c4490a26703112a5cc1d0923fd697a33406bd5a1c00e0013b09a70",
            "votes": "0",
            "active": false
        },
        {
            "publickey": "024c7b7fb6c310fccf1ba33b082519d82964ea93868d676662d4a59ad548df0e7d",
            "votes": "37927248",
            "active": true
        },
        {
            "publickey": "025bdf3f181f53e9696227843950deb72dcd374ded17c057159513c3d0abe20b64",
            "votes": "37927248",
            "active": true
        },
    ]
    }  

getversion
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getversion

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/getversion',
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
Returns the status::

    {
    "status": 200,
    "values": {
        "port": 10323,
        "nonce": 574345106,
        "useragent": "/Neo:2.10.3/"
        }
    }  

invokefunction
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/invokefunction

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    script hash         
    operation           {
    params              "script_hash": "af7c7328eee5a275a3bcaee2bf0cf662b5e739be",
                        "operation": "balanceOf",
                        "params": "91b83e96f2a7c4fdf0c1688441ec61986c7cae26"
                        } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/invokefunction',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"script_hash":"af7c7328eee5a275a3bcaee2bf0cf662b5e739be","operation":"balanceOf","params":"91b83e96f2a7c4fdf0c1688441ec61986c7cae26"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200
    "values":
    } 

invokescript
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/invokescript

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    script  
                {
                "script": "00046e616d656724058e5e1b6008847cd662728549088a9ee82191"
                } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/invokescript',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"script":"00046e616d656724058e5e1b6008847cd662728549088a9ee82191"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": {
        "port": 10323,
        "nonce": 574345106,
        "useragent": "/Neo:2.10.3/"
        }
    }  

sendrawtransaction
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/sendrawtransaction

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    hex 
                {
                "hex": "80000001195876cb34364dc38b730077156c6bc3a7fc570044a66fbfeeea56f71327e8ab0000029b7cffdaa674beae0f930ebe6085af9093e5fe56b34a5c220ccdcf6efc336fc500c65eaf440000000f9a23e06f74cf86b8827a9108ec2e0f89ad956c9b7cffdaa674beae0f930ebe6085af9093e5fe56b34a5c220ccdcf6efc336fc50092e14b5e00000030aab52ad93f6ce17ca07fa88fc191828c58cb71014140915467ecd359684b2dc358024ca750609591aa731a0b309c7fb3cab5cd0836ad3992aa0a24da431f43b68883ea5651d548feb6bd3c8e16376e6e426f91f84c58232103322f35c7819267e721335948d385fae5be66e7ba8c748ac15467dcca0693692dac"
                } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/sendrawtransaction',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"hex":"80000001195876cb34364dc38b730077156c6bc3a7fc570044a66fbfeeea56f71327e8ab0000029b7cffdaa674beae0f930ebe6085af9093e5fe56b34a5c220ccdcf6efc336fc500c65eaf440000000f9a23e06f74cf86b8827a9108ec2e0f89ad956c9b7cffdaa674beae0f930ebe6085af9093e5fe56b34a5c220ccdcf6efc336fc50092e14b5e00000030aab52ad93f6ce17ca07fa88fc191828c58cb71014140915467ecd359684b2dc358024ca750609591aa731a0b309c7fb3cab5cd0836ad3992aa0a24da431f43b68883ea5651d548feb6bd3c8e16376e6e426f91f84c58232103322f35c7819267e721335948d385fae5be66e7ba8c748ac15467dcca0693692dac"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": 
    }  

validateaddress
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api that been use for call rpc::

    http://integrationhub.okwave.asia:3333/api/v2/neomainnet/validateaddress

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    address         
                    {
                    "address": "AQVh2pG732YvtNaxEGkQUei3YA4cvo7d2i"
                    } 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/neomainnet/validateaddress',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"address":"AQVh2pG732YvtNaxEGkQUei3YA4cvo7d2i"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the status::

    {
    "status": 200,
    "values": {
        "address": "AQVh2pG732YvtNaxEGkQUei3YA4cvo7d2i",
        "isvalid": true
        }
    }  

