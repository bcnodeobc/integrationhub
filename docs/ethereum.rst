========
Ethereum
========

All RPC included are based on web3. 

.. note::  Make sure to registerToken first before requesting rpc and replace the token in Authoraization headers. http://integrationhub.okwave.asia:3333/api/v2/registerToken

transactionBlockTimeout
=======================

The amount of new blocks it should wait until the first confirmation happens.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/transactionBlockTimeout

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::

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
Results::

    {
    "status": 200,
    "values": 50
    }

------------------------------------------------------------------------------

transactionPollingTimeout
=========================

This rpc is used over HTTP connections. It defines the number of seconds Web3 will wait for a receipt which confirms that a transaction was mined by the network.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/transactionPollingTimeout

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::

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
Results::

    {
    "status": 200,
    "values": 750
    }

------------------------------------------------------------------------------

getHashrate
===========

The number of hashes per second that the node is mining with.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getHashrate

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::

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
Results::

    {
    "status": 200,
    "values": 0
    }

------------------------------------------------------------------------------

getGasPrice
===========

The current gas price oracle. The gas price is determined by the last few blocks median gas price.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getGasPrice

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::

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
Results::

    {
    "status": 200,
    "values": "20000001459"
    }

------------------------------------------------------------------------------

getBlockNumber
==============

The number of the most recent block.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getBlockNumber

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::

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
Results::

    {
    "status": 200,
    "values": 11090988
    }

------------------------------------------------------------------------------

getStorageAt
============

Get the storage at a specific position of an address.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getStorageAt

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    address         The address to get storage and the index position of the storage
    position        {
                    "address": "0x407d73d8a49eeb85d32cf465507dd71d507100c1",
                    "position": 0
                    } 

Example
--------
Example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getStorageAt',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjA0ODkyMjE5LCJleHAiOjE2MDU0OTcwMTl9.fcLs3o7UlljwCh6NnHI-7mW3gVdGPR2X2WACW3iUxKo',
            'Content-Type': 'application/json'
        },
    body: JSON.stringify({"address":"0x407d73d8a49eeb85d32cf465507dd71d507100c1","position":0})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Results::

    {
    "status": 200,
    "values": "0x0000000000000000000000000000000000000000000000000000000000000000"
    }

------------------------------------------------------------------------------

getCode
========

Get the code at a specific address.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getCode

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    address     The address to get the code from
                {
                "address": "0x407d73d8a49eeb85d32cf465507dd71d507100c1"
                }

Example
--------
Example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getCode',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjA0ODkyMjE5LCJleHAiOjE2MDU0OTcwMTl9.fcLs3o7UlljwCh6NnHI-7mW3gVdGPR2X2WACW3iUxKo',
            'Content-Type': 'application/json'
        },
    body: JSON.stringify({"address":"0x407d73d8a49eeb85d32cf465507dd71d507100c1"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Results::

    {
    "status": 200,
    "values": "0x"
    }

------------------------------------------------------------------------------

getBlock
========

The block matching the block number or block hash.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getBlock

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    blockNumber     The block number or block hash
                    {
                    "blockNumber":"latest" 
                    }

Example
--------
Example::

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
Results::

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

------------------------------------------------------------------------------

getBlockTransactionCount
========================

The number of transaction in a given block.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getBlockTransactionCount

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    blockNumber     Get the latest block
                    {
                    "blockNumber":"latest"
                    }

Example
--------
Example::
    
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
Results::

    {
    "status": 200,
    "values": 248
    }

------------------------------------------------------------------------------

getBlockUncleCount
==================

The number of uncles in a block from a block matching the given block hash.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getBlockUncleCount

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    blockNumber     The block number or hash
                    {
                    "blockNumber":"latest"
                    }

Example
--------
Example::
    
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
Results::

    {
    "status": 200,
    "values": 1
    }

------------------------------------------------------------------------------

getUncle
========

The blocks uncle by a given uncle index position.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getUncle

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    blockNumber     The block number or hash and the index position of the uncle
    uncleIndex      {
                    "blockNumber": "latest",
                    "uncleIndex": "0"
                    }

Example
--------
Example::
    
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
Results::

    {
    "status": 200,
    "values": null
    }

------------------------------------------------------------------------------

getTransaction
==============

The transaction matching that given transaction hash.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getTransaction

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    transactionHash     The transaction hash.
                        {
                        "transactionHash": "0xc919e0b9dec70ae9fac16af491928806210581a82eca8e25e490ebacee324b68"
                        }

Example
--------
Example::
    
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
Results::

    {
    "status": 200,
    "values": null
    }

------------------------------------------------------------------------------

getTransactionFromBlock
=======================

The transaction based on a block hash or number and the transaction’s index position.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getTransactionFromBlock

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    hashString      A block number or hash and the transaction’s index position
    indexNumber     {
                    "hashString": "latest",
                    "indexNumber": "3"
                    }

Example
--------
Example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getTransactionFromBlock',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"hashString":"latest","indexNumber":"0"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Results::

    {
    "status": 200,
    "values": null
    }

------------------------------------------------------------------------------

getTransactionReceipt
=====================

The receipt of a transaction by transaction hash.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getTransactionReceipt

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    hash    The transaction hash.
            {
            "hash": "0xc919e0b9dec70ae9fac16af491928806210581a82eca8e25e490ebacee324b68"
            }

Example
--------
Example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getTransactionReceipt',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"hash":"0xc919e0b9dec70ae9fac16af491928806210581a82eca8e25e490ebacee324b68"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Results::

    {
    "status": 200,
    "values": null
    }

------------------------------------------------------------------------------

getTransactionCount
===================

The number of transactions sent from this address.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getTransactionCount

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    address     The address to get the numbers of transactions from
                {
                "address": "0xceb21b8ce14e287a106bd01f5c92dac970c1efd3"
                }

Example
--------
Example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getTransactionCount',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"address":"0xceb21b8ce14e287a106bd01f5c92dac970c1efd3"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Results::

    {
    "status": 200,
    "values": 0
    }

------------------------------------------------------------------------------

sendSignedTransaction
=====================

Sends an already signed transaction.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/sendSignedTransaction

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    serial tx    Signed transaction data in HEX format
                {
                "serializedTx": "0xf86c04853e660b780082520894b43f7f7af34c4b214456bd98d468d533865fbb458806f05b59d3b20000801ca00de040fe31ea5a8a275fc704e7fc8f7cdbaa6a44a770027c421773bfa7fd6099a07b0452c6a223b50fe8c4a1280f7782470b1ea277eda4ab18ac2ce20e9f08f342"
                }

Example
--------
Example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/sendSignedTransaction',
    'headers': {
        'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({"serializedTx":"0xf86c04853e660b780082520894b43f7f7af34c4b214456bd98d468d533865fbb458806f05b59d3b20000801ca00de040fe31ea5a8a275fc704e7fc8f7cdbaa6a44a770027c421773bfa7fd6099a07b0452c6a223b50fe8c4a1280f7782470b1ea277eda4ab18ac2ce20e9f08f342"})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Results::

    {
    "status": 200,
    "values": 
    }

------------------------------------------------------------------------------

getNodeInfo
===========

The current client version.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getNodeInfo

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getNodeInfo',
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
Results::

    {
    "status": 200,
    "values": "Geth/v1.9.10-stable-58cf5686/linux-amd64/go1.13.6"
    }

------------------------------------------------------------------------------

getProtocolVersion
==================

The ethereum protocol version of the node.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getProtocolVersion

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getProtocolVersion',
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
Results::

    {
    "status": 200,
    "values": "0x40"
    }

------------------------------------------------------------------------------

isSyncing
=========

Checks if the node is currently syncing and returns either a syncing object.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/isSyncing

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/isSyncing',
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
Results::

    {
    "status": 200,
    "values": false
    }

------------------------------------------------------------------------------

getPastLogs
===========

The past logs, matching the given options.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getPastLogs

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    address         An address or a list of addresses to only get logs from particular account(s) and an array of values which must each appear in the log entries
    topics          {
                    "address": "0x11f4d0A3c12e86B4b5F39B213F7E19D048276DAe",
                    "topics": [
                        "0x033456732123ffff2342342dd12342434324234234fd234fd23fd4f23d4234"
                        ]
                    }

Example
--------
Example::
    
    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.eth/getPastLogs',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjA0ODkyMjE5LCJleHAiOjE2MDU0OTcwMTl9.fcLs3o7UlljwCh6NnHI-7mW3gVdGPR2X2WACW3iUxKo',
            'Content-Type': 'application/json'
        },
    body: JSON.stringify({"address":"0x11f4d0A3c12e86B4b5F39B213F7E19D048276DAe","topics":["0x033456732123ffff2342342dd12342434324234234fd234fd23fd4f23d4234"]})
    };
    request(options, function (error, response) {
        if (error) throw new Error(error);
        console.log(response.body);
    });

Response
--------
Results::

    {
    "status": 200,
    "values": [
        {
            "address": "0xdAC17F958D2ee523a2206206994597C13D831ec7",
            "topics": [
                "0xddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef",
                "0x0000000000000000000000005bcbdfb6cc624b959c39a2d16110d1f2d9204f72",
                "0x000000000000000000000000c604e69082c6c0a4c705691141ec37f0ef094d27"
            ],
            "data": "0x000000000000000000000000000000000000000000000000000000001dcd6500",
            "blockNumber": 11221072,
            "transactionHash": "0x6c65db22f3ec848476cfc13bf5af650a4e7fb35c27c8f7e0bbbed19b18d7d30d",
            "transactionIndex": 12,
            "blockHash": "0x31348861b687857328d24bafcf6b3a1371d783fe9997c424c6a85415fa970cf2",
            "logIndex": 0,
            "removed": false,
            "id": "log_d41609af"
        },
        .....
        {
            "address": "0x2F8fF07E607c6E489cdEa3D107AbeCC9b8024531",
            "topics": [
                "0x8c5be1e5ebec7d5bd14f71427d1e84f3dd0314c0f7b2291e5b200ac8c7c3b925",
                "0x000000000000000000000000a2b26fdcf2f328d01bf4cc29c7c16b039dc6f772",
                "0x0000000000000000000000007a250d5630b4cf539739df2c5dacb4c659f2488d"
            ],
            "data": "0xffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff",
            "blockNumber": 11221072,
            "transactionHash": "0x96237a7bd08d93fc0100a3731381ebd450007215586bb0c6129c504fe5201c84",
            "transactionIndex": 245,
            "blockHash": "0x31348861b687857328d24bafcf6b3a1371d783fe9997c424c6a85415fa970cf2",
            "logIndex": 309,
            "removed": false,
            "id": "log_d51187a6"
        }
    ]
}

------------------------------------------------------------------------------

getPeerCount
============

The number of peers connected to.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.*.net/getPeerCount

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.*.net/getPeerCount',
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
Results::

    {
    "status": 200,
    "values": 14
    }

------------------------------------------------------------------------------

getId
========

The current network ID.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.*.net/getId

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.*.net/getId',
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
Results::

    {
    "status": 200,
    "values": 1
    }

------------------------------------------------------------------------------

isListening
===========

Checks if the node is listening for peers.

Example::

    http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.*.net/isListening

Headers
--------
Need to set headers::

    Key             Value

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

Example
--------
Example::
    
    var request = require('request');
    var options = {
    'method': 'POST',
    'url': 'http://integrationhub.okwave.asia:3333/api/v2/ethmainnet/web3.*.net/isListening',
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
Results::

    {
    "status": 200,
    "values": true
    }
