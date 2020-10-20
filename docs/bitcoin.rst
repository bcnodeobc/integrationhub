========
BITCOIN
========

$project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

- Be awesome
- Make things faster

getblockcount
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getblockcount

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    bitcoin address for account 

Example
--------
example::

    {
    }

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": 653506
    }

getbestblockhash
========

bitcoin rpc getbestblockhash.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getbestblockhash

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    bitcoin address for account 

Example
--------
example::

    {
    }

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": "0000000000000000000192e1fe636f862d3416bbc13a3a2a084fd1e9775aa903"
    }

getblock
========

this bitcoin rpc for getblock.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getblock

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    blockhash   hash of the block

Example
--------
example::

    {
    "blockhash": "0000000000000293c83a20b0e537c52fb7903c3b5d6e358400d5574ea0ec33ba"
    }

Response
--------
Returns the current block number::

    {
        "success": ,
        "values": ""
    }

getblockchaininfo
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getblockchaininfo

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    bitcoin address for account 

Example
--------
example::

    {
    }

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": {
        "chain": "main",
        "blocks": 653506,
        "headers": 653506,
        "bestblockhash": "0000000000000000000192e1fe636f862d3416bbc13a3a2a084fd1e9775aa903",
        "difficulty": 19997335994446.11,
        "mediantime": 1603158828,
        "verificationprogress": 0.9999927472184578,
        "initialblockdownload": false,
        "chainwork": "000000000000000000000000000000000000000014e050ddea8491609bc1e1d2",
        "size_on_disk": 347139991490,
        "pruned": false,
        "softforks": {
            "bip34": {
                "type": "buried",
                "active": true,
                "height": 227931
            },
            "bip66": {
                "type": "buried",
                "active": true,
                "height": 363725
            },
            "bip65": {
                "type": "buried",
                "active": true,
                "height": 388381
            },
            "csv": {
                "type": "buried",
                "active": true,
                "height": 419328
            },
            "segwit": {
                "type": "buried",
                "active": true,
                "height": 481824
            }
        },
        "warnings": ""
        }
    }

getblockhash
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getblockhash

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
Need parameters::

    set value height block

Example
--------
example::

    {
    "height": 1457
    }

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": "00000000c1b653c16878482f16d9d25f59214468f79ceceb6b0b58020d83aab5"
    }

getblockheader
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getblockheader

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    bitcoin address for account 

Example
--------
example::

    {
    "blockhash": "00000000438e70988896a0e26183820bf06a693b69062532432ea5034e8afd19"
    }

Response
--------
Returns the current block number::

    {
        "success": ,
        "values": ""
    }

getblockstats
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getblockstats

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    bitcoin address for account 

Example
--------
example::

    { 
        "height": "100" 
    }

Response
--------
Returns the current block number::

    {
        "success": ,
        "values": ""
    }

getdifficulty
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getdifficulty

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    bitcoin address for account 

Example
--------
example::

    {
    }

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": 19997335994446.11
}   