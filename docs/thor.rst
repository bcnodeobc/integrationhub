========
THOR
========

This project using javascript to testing the rpc.

User can test the rpc by using Postman nodejs - request.


get
========

project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Returns the current block number::

    http://integrationhub.okwave.asia:3333/api/v2/thorhammer/web3.*.net/

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
    

Response
--------
Returns the current block timeout::

    {
    "status": 200,
    "values": 
    }
