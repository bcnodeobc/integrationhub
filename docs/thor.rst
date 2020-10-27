========
THOR
========

This project using javascript to testing the rpc.

User can test the rpc by using Postman nodejs - request.


getPeerCount
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.*.net/getPeerCount

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.*.net/getPeerCount',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": 5
    }

transactionBlockTimeout
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.*.net/transactionBlockTimeout

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/transactionBlockTimeout',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": 
    }

transactionPollingTimeout
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/transactionPollingTimeout

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/transactionPollingTimeout',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": 
    }

getGasPrice
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getGasPrice

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getGasPrice',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": "3"
    }

getHashrate
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getHashrate

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getHashrate',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": 0
    }

getBlockNumber
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getBlockNumber

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getBlockNumber',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": 1403318
    }

getBalance
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getBalance

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
                    "address": "0xceb21b8ce14e287a106bd01f5c92dac970c1efd3"
                    }

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getBalance',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
Returns the status::

    {
    "status": 200,
    "values": "0"
    }

getCode
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getCode

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
                    "address": "0xceb21b8ce14e287a106bd01f5c92dac970c1efd3"
                    }

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getCode',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
Returns the status::

    {
    "status": 200,
    "values": "0x"
    }

getBlock
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getBlock

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    blockNumber
                    {
                    "blockNumber":"latest"
                    }

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getBlock',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
Returns the status::

    {
    "status": 200,
    "values": {
        "difficulty": "2",
        "extraData": "0xd883010906846765746888676f312e31332e31856c696e75780000000000000050a6351461b87fd043902f7e5baf12367be4fc31b7307efbf4a6d017c8fb834b7b9b266b597e5fed86849d2f8f7332599d312aef86db04c2d81a2cc1b152e84400",
        "gasLimit": 9000000000000,
        "gasUsed": 0,
        "hash": "0x3ba14dc48b4ea96d3b2f6c3e0991eefcf99674b13d6d44d44dcda714942cee82",
        "logsBloom": "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
        "miner": "0x0000000000000000000000000000000000000000",
        "mixHash": "0x0000000000000000000000000000000000000000000000000000000000000000",
        "nonce": "0x0000000000000000",
        "number": 1403342,
        "parentHash": "0xcd9d30baf86dd4f26024ef938d3c6ff87ae97731c74a0f58b339be5b8a5a462a",
        "receiptsRoot": "0x56e81f171bcc55a6ff8345e692c0f86e5b48e01b996cadc001622fb5e363b421",
        "sha3Uncles": "0x1dcc4de8dec75d7aab85b567b6ccd41ad312451b948a7413f0a142fd40d49347",
        "size": 612,
        "stateRoot": "0x86884f759890ea27b6ecd347c1d71767a2871e89cf72546d96598c34a1d7850a",
        "timestamp": 1603764687,
        "totalDifficulty": "2806684",
        "transactions": [],
        "transactionsRoot": "0x56e81f171bcc55a6ff8345e692c0f86e5b48e01b996cadc001622fb5e363b421",
        "uncles": []
        }
    }

getBlockTransactionCount
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getBlockTransactionCount

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    blockNumber
                    {
                    "blockNumber":"latest"
                    }

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getBlockTransactionCount',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
Returns the status::

    {
    "status": 200,
    "values": "0"
    }

getBlockUncleCount
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getBlockUncleCount

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
                    "blockNumber":"latest"
                    }

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getBlockUncleCount',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
Returns the status::

    {
    "status": 200,
    "values": 0
    }

getUncle
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getUncle

Headers
--------
Need to set headers::

    Content-Type    application/json

    Authorization   OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzMTU3NjMzLCJleHAiOjE2MDM3NjI0MzN9.71my1T-2IxQNJhNNu-aRX7N3TLo9BqAczyGWX1ph2vA

Parameters
--------
No need parameters::

    block Number
                        {
                        "blockNumber": "latest",
                        "uncleIndex": "0"
                        }

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getUncle',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
Returns the status::

    {
    "status": 200,
    "values": null
    }

getId
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.*.net/getId

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.*.net/getId',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": 5234
    }

isListening
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.*.net/isListening

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.*.net/isListening',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": true
    }

getProtocolVersion
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getProtocolVersion

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getProtocolVersion',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": "0x3f"
    }

isSyncing
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/isSyncing

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/isSyncing',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": false
    }

isMining
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/isMining

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/isMining',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": false
    }

getStorageAt
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getStorageAt

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getStorageAt',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": 0
    }

getPastLogs
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getPastLogs

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
                    "address": "0xceb21b8ce14e287a106bd01f5c92dac970c1efd3"
                    }

Example
--------
example::

    var request = require('request');
    var options = {
        'method': 'POST',
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getPastLogs',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
Returns the status::

    {
    "status": 200,
    "values": 
    }

getChainId
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getChainId

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getChainId',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": 5234
    }

getNodeInfo
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getNodeInfo

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getNodeInfo',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
    "values": "Geth/v1.9.6-stable-057d336e/linux-amd64/go1.10.4"
    }

getAccounts
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Api for this rpc::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getAccounts

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
        'url': 'http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.eth/getAccounts',
        'headers': {
            'Authorization': 'OBC eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjAzNzYyNjY5LCJleHAiOjE2MDQzNjc0Njl9.L9MEaOdEgKPk-eVHdldaMw5I_XmKgUJwHg3aV4HVvsU',
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
        "0x8062ec81cedD539A7Ba0Ba87B9a2D1aF14AA2D46"
        ]
    }
