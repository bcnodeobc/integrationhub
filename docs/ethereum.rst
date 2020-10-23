========
ETHEREUM
========

This project using javascript to testing the rpc.

User can test the rpc by using Postman nodejs - request.

- Be awesome
- Make things faster

transactionBlockTimeout
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia/api/v2/ethmainnet/web3.eth/transactionBlockTimeout

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    ethereum address for account 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/transactionBlockTimeout',
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
    "values": 50
    }

transactionPollingTimeout
========

ethereum rpc transactionPollingTimeout.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/ethmainnet/web3.eth/transactionPollingTimeout

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    ethereum address for account 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/transactionPollingTimeout',
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
Returns the transaction Polling Timeout::

    {
    "status": 200,
    "values": 750
    }

getHashrate
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia/api/v2/ethmainnet/web3.eth/getHashrate

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    ethereum address for account 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getHashrate',
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
    "values": 0
    }

getGasPrice
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia/api/v2/ethmainnet/web3.eth/getGasPrice

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    ethereum address for account 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getGasPrice',
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
    "values": "20000001459"
    }

getBlockNumber
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia/api/v2/ethmainnet/web3.eth/getBlockNumber

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    ethereum address for account 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getBlockNumber',
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
    "values": 11090988
    }

getStorageAt
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia/api/v2/ethmainnet/web3.eth/getStorageAt

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    ethereum address for account 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getStorageAt',
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
    "status": ,
    "values": ""
    }

getCode
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the ::

    http://integrationhub.okwave.asia/api/v2/ethmainnet/web3.eth/getCode

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    ethereum address for account 

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getCode',
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
Returns the code::

    {
    "status": 200,
    "values": "0x"
    }

getBlock
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the ::

    http://integrationhub.okwave.asia/api/v2/ethmainnet/web3.eth/getBlock

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    blockNumber     address for account
                    {
                    "blockNumber":"latest" 
                    }
                        

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getBlock',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
            'Content-Type': 'application/json'
    },
    body: JSON.stringify({"blockNumber":"latest"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the code::

    {
    "status": 200,
    "values": {
        "difficulty": "3283105782578062",
        "extraData": "0x6574682d70726f2d687a6f2d74303035",
        "gasLimit": 12474811,
        "gasUsed": 12458310,
        "hash": "0x304ae091240c163d6bba3c185a231561e652b288323fe025c423a4b689355e03",
        "logsBloom": "0x4460218c55406620444026c1904510208071a2a4d41ac610580917820088034500d4010310c04b82f125eaa8522201d8927b441e0b48000b2c4dcf8435282c005b8860c09b405930cc043a2a540119b090c229165363349423e28321820470101c603f8456688400d060e7d400645a93a22920022c082e262028033c60ae854228ca95212acd2cd086c909c40a98081201b49b57b5a0902b0159c043e4196f880afe45ad1e646e448ce0088048149c4902030690e48202896c5b10ae02c04228b7298c9a080a18480a9fc5005042814d30413603530f819fc52a5112c180a208523260c321183044000b24c4112162278530aac4463c935ad030fb838aa09224",
        "miner": "0x5A0b54D5dc17e0AadC383d2db43B0a0D3E029c4c",
        "mixHash": "0xb1033124f5b12a340850ff39994c02fc7d9f35155610db382ea7983e8dc77423",
        "nonce": "0xf6085d174470b114",
        "number": 11106835,
        "parentHash": "0xfd5141b7f3468de3ffa050d4521de95f79a79dbf988e47fc4800a29a1165590e",
        "receiptsRoot": "0xa8f0069588af87ae5b42e121b5baa91cf2df4d60791309e83f9db277bfd2da7b",
        "sha3Uncles": "0x1dcc4de8dec75d7aab85b567b6ccd41ad312451b948a7413f0a142fd40d49347",
        "size": 25928,
        "stateRoot": "0x2867691f276a6bf750d6eb336170b28efb9f412c85fbcf08e342623f0ebecda7",
        "timestamp": 1603380975,
        "totalDifficulty": "18201459894245119072846",
        "transactions": [
            "0x4e9f3ec2efc14d4641cbde5dd60a8df18a9cf27c6ce96bd446a907f5dbff8038",
            "0x501822209a669595531ae18044b95fdcd9809aaff87e163a53f726978cf3052b",
            "0x9ba57c78effeed2246148bba42394f6206df2bfba3d151c7ba1fa3b4226f1efa"
        ],
        "transactionsRoot": "0xf07a0da121dc485459eb59b3818bcb607ca2c909ea12062d767090687645d3dd",
        "uncles": []
    }
}

getBlockTransactionCount
========

this ethereum rpc for getBlockTransactionCount.

Api for this rpc::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getBlockTransactionCount

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    blockNumber     get the latest block
                    {
                    "blockNumber":"latest"
                    }

Example
--------
example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getBlockTransactionCount',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"blockNumber":"latest"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": 248
    }

getBlockUncleCount
========

this ethereum rpc for getBlockUncleCount.

Api for this rpc::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getBlockUncleCount

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    blockNumber     get the latest block
                    {
                    "blockNumber":"latest"
                    }

Example
--------
example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getBlockUncleCount',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"blockNumber":"latest"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": 0
    }

getUncle
========

this ethereum rpc for getUncle.

Api for this rpc::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getUncle

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    blockNumber     get the latest block
    uncleIndex      {
                    "blockNumber": "latest",
                    "uncleIndex": "0"
                    }

Example
--------
example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getUncle',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"blockNumber":"latest","uncleIndex":"0"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": null
    }

getTransaction
========

this ethereum rpc for getTransaction.

Api for this rpc::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getTransaction

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    transactionHash     get the latest block
                        {
                        "transactionHash": "0xc919e0b9dec70ae9fac16af491928806210581a82eca8e25e490ebacee324b68"
                        }

Example
--------
example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getTransaction',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
      body: JSON.stringify({"transactionHash":"0xc919e0b9dec70ae9fac16af491928806210581a82eca8e25e490ebacee324b68"})
    };
    request(options, function (error, response) {
    if (error) throw new Error(error);
    console.log(response.body);
    });

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": null
    }
