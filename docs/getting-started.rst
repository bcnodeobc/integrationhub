Getting Started
---------------

Usage
=====

1. User should registerToken before start to request function. 

    http://integrationhub.okwave.asia:3333/api/v2/registerToken

Results::

    {
    "status": 200,
    "values": {
        "success": true,
        "message": "Authentication successful!",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoib2JjIiwiaWF0IjoxNjA1MDY4NDcyLCJleHAiOjE2MDU2NzMyNzJ9.nIZ-ItuWK_9zsXPyZ8yblhFFMNjB3Vku9GKABTFFRvs"
    }


2. Change header value under Authorization's key with token value from previous step and add OBC in front of the token.

3. Enjoy !.


Authors
=======

* Aizu Zuyyin
* Mohamad Fazuan
* Shahrizal
* Ridzuan
* Hisham

.. note::  TEAM BLOCKCHAIN