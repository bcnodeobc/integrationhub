========
BITCOIN
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

bitcoin rpc get block chain info.

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

bitcoin rpc for get block hash.

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

bitcoin rpc for get block header.

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

bitcoin rpc for get blockstats.

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

bitcoin rpc for getdifficulty .

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

getmemoryinfo
========

bitcoin rpc for get memory info.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getmemoryinfo

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
        "locked": {
            "used": 117056,
            "free": 145088,
            "total": 262144,
            "locked": 262144,
            "chunks_used": 3656,
            "chunks_free": 2
            }
        }
    }   

getrpcinfo
========

bitcoin rpc for getrpcinfo .

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getrpcinfo

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
        "active_commands": [
            {
                "method": "getrpcinfo",
                "duration": 1037
            }
        ],
        "logpath": "/var/lib/bitcoind/debug.log"
        }
    }   

help
========

bitcoin rpc for help .

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/help

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
    "values": "== Blockchain ==\ngetbestblockhash\ngetblock \"blockhash\" ( verbosity )\ngetblockchaininfo\ngetblockcount\ngetblockfilter \"blockhash\" ( \"filtertype\" )\ngetblockhash height\ngetblockheader \"blockhash\" ( verbose )\ngetblockstats hash_or_height ( stats )\ngetchaintips\ngetchaintxstats ( nblocks \"blockhash\" )\ngetdifficulty\ngetmempoolancestors \"txid\" ( verbose )\ngetmempooldescendants \"txid\" ( verbose )\ngetmempoolentry \"txid\"\ngetmempoolinfo\ngetrawmempool ( verbose )\ngettxout \"txid\" n ( include_mempool )\ngettxoutproof [\"txid\",...] ( \"blockhash\" )\ngettxoutsetinfo\npreciousblock \"blockhash\"\npruneblockchain height\nsavemempool\nscantxoutset \"action\" [scanobjects,...]\nverifychain ( checklevel nblocks )\nverifytxoutproof \"proof\"\n\n== Control ==\ngetmemoryinfo ( \"mode\" )\ngetrpcinfo\nhelp ( \"command\" )\nlogging ( [\"include_category\",...] [\"exclude_category\",...] )\nstop\nuptime\n\n== Generating ==\ngeneratetoaddress nblocks \"address\" ( maxtries )\n\n== Mining ==\ngetblocktemplate ( \"template_request\" )\ngetmininginfo\ngetnetworkhashps ( nblocks height )\nprioritisetransaction \"txid\" ( dummy ) fee_delta\nsubmitblock \"hexdata\" ( \"dummy\" )\nsubmitheader \"hexdata\"\n\n== Network ==\naddnode \"node\" \"command\"\nclearbanned\ndisconnectnode ( \"address\" nodeid )\ngetaddednodeinfo ( \"node\" )\ngetconnectioncount\ngetnettotals\ngetnetworkinfo\ngetnodeaddresses ( count )\ngetpeerinfo\nlistbanned\nping\nsetban \"subnet\" \"command\" ( bantime absolute )\nsetnetworkactive state\n\n== Rawtransactions ==\nanalyzepsbt \"psbt\"\ncombinepsbt [\"psbt\",...]\ncombinerawtransaction [\"hexstring\",...]\nconverttopsbt \"hexstring\" ( permitsigdata iswitness )\ncreatepsbt [{\"txid\":\"hex\",\"vout\":n,\"sequence\":n},...] [{\"address\":amount},{\"data\":\"hex\"},...] ( locktime replaceable )\ncreaterawtransaction [{\"txid\":\"hex\",\"vout\":n,\"sequence\":n},...] [{\"address\":amount},{\"data\":\"hex\"},...] ( locktime replaceable )\ndecodepsbt \"psbt\"\ndecoderawtransaction \"hexstring\" ( iswitness )\ndecodescript \"hexstring\"\nfinalizepsbt \"psbt\" ( extract )\nfundrawtransaction \"hexstring\" ( options iswitness )\ngetrawtransaction \"txid\" ( verbose \"blockhash\" )\njoinpsbts [\"psbt\",...]\nsendrawtransaction \"hexstring\" ( maxfeerate )\nsignrawtransactionwithkey \"hexstring\" [\"privatekey\",...] ( [{\"txid\":\"hex\",\"vout\":n,\"scriptPubKey\":\"hex\",\"redeemScript\":\"hex\",\"witnessScript\":\"hex\",\"amount\":amount},...] \"sighashtype\" )\ntestmempoolaccept [\"rawtx\",...] ( maxfeerate )\nutxoupdatepsbt \"psbt\" ( [\"\",{\"desc\":\"str\",\"range\":n or [n,n]},...] )\n\n== Util ==\ncreatemultisig nrequired [\"key\",...] ( \"address_type\" )\nderiveaddresses \"descriptor\" ( range )\nestimatesmartfee conf_target ( \"estimate_mode\" )\ngetdescriptorinfo \"descriptor\"\nsignmessagewithprivkey \"privkey\" \"message\"\nvalidateaddress \"address\"\nverifymessage \"address\" \"signature\" \"message\"\n\n== Wallet ==\nabandontransaction \"txid\"\nabortrescan\naddmultisigaddress nrequired [\"key\",...] ( \"label\" \"address_type\" )\nbackupwallet \"destination\"\nbumpfee \"txid\" ( options )\ncreatewallet \"wallet_name\" ( disable_private_keys blank \"passphrase\" avoid_reuse )\ndumpprivkey \"address\"\ndumpwallet \"filename\"\nencryptwallet \"passphrase\"\ngetaddressesbylabel \"label\"\ngetaddressinfo \"address\"\ngetbalance ( \"dummy\" minconf include_watchonly avoid_reuse )\ngetbalances\ngetnewaddress ( \"label\" \"address_type\" )\ngetrawchangeaddress ( \"address_type\" )\ngetreceivedbyaddress \"address\" ( minconf )\ngetreceivedbylabel \"label\" ( minconf )\ngettransaction \"txid\" ( include_watchonly verbose )\ngetunconfirmedbalance\ngetwalletinfo\nimportaddress \"address\" ( \"label\" rescan p2sh )\nimportmulti \"requests\" ( \"options\" )\nimportprivkey \"privkey\" ( \"label\" rescan )\nimportprunedfunds \"rawtransaction\" \"txoutproof\"\nimportpubkey \"pubkey\" ( \"label\" rescan )\nimportwallet \"filename\"\nkeypoolrefill ( newsize )\nlistaddressgroupings\nlistlabels ( \"purpose\" )\nlistlockunspent\nlistreceivedbyaddress ( minconf include_empty include_watchonly \"address_filter\" )\nlistreceivedbylabel ( minconf include_empty include_watchonly )\nlistsinceblock ( \"blockhash\" target_confirmations include_watchonly include_removed )\nlisttransactions ( \"label\" count skip include_watchonly )\nlistunspent ( minconf maxconf [\"address\",...] include_unsafe query_options )\nlistwalletdir\nlistwallets\nloadwallet \"filename\"\nlockunspent unlock ( [{\"txid\":\"hex\",\"vout\":n},...] )\nremoveprunedfunds \"txid\"\nrescanblockchain ( start_height stop_height )\nsendmany \"\" {\"address\":amount} ( minconf \"comment\" [\"address\",...] replaceable conf_target \"estimate_mode\" )\nsendtoaddress \"address\" amount ( \"comment\" \"comment_to\" subtractfeefromamount replaceable conf_target \"estimate_mode\" avoid_reuse )\nsethdseed ( newkeypool \"seed\" )\nsetlabel \"address\" \"label\"\nsettxfee amount\nsetwalletflag \"flag\" ( value )\nsignmessage \"address\" \"message\"\nsignrawtransactionwithwallet \"hexstring\" ( [{\"txid\":\"hex\",\"vout\":n,\"scriptPubKey\":\"hex\",\"redeemScript\":\"hex\",\"witnessScript\":\"hex\",\"amount\":amount},...] \"sighashtype\" )\nunloadwallet ( \"wallet_name\" )\nwalletcreatefundedpsbt [{\"txid\":\"hex\",\"vout\":n,\"sequence\":n},...] [{\"address\":amount},{\"data\":\"hex\"},...] ( locktime options bip32derivs )\nwalletlock\nwalletpassphrase \"passphrase\" timeout\nwalletpassphrasechange \"oldpassphrase\" \"newpassphrase\"\nwalletprocesspsbt \"psbt\" ( sign \"sighashtype\" bip32derivs )\n\n== Zmq ==\ngetzmqnotifications"
    }  

uptime
========

bitcoin rpc for uptime.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/uptime

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
    "values": 423824
    }  

getconnectioncount
========

bitcoin rpc for getconnectioncount.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getconnectioncount

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
    "values": 10
    }  

getnettotals
========

bitcoin rpc for getnettotals.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getnettotals

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
        "totalbytesrecv": 3299246288,
        "totalbytessent": 40608233565,
        "timemillis": 1603167889678,
        "uploadtarget": {
            "timeframe": 86400,
            "target": 0,
            "target_reached": false,
            "serve_historical_blocks": true,
            "bytes_left_in_cycle": 0,
            "time_left_in_cycle": 0
            }
        }
    } 

getnetworkinfo
========

bitcoin rpc for getnetworkinfo.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getnetworkinfo

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
        "version": 190001,
        "subversion": "/Satoshi:0.19.0.1/",
        "protocolversion": 70015,
        "localservices": "0000000000000409",
        "localservicesnames": [
            "NETWORK",
            "WITNESS",
            "NETWORK_LIMITED"
        ],
        "localrelay": true,
        "timeoffset": 0,
        "networkactive": true,
        "connections": 10,
        "networks": [
            {
                "name": "ipv4",
                "limited": false,
                "reachable": true,
                "proxy": "",
                "proxy_randomize_credentials": false
            },
            {
                "name": "ipv6",
                "limited": false,
                "reachable": true,
                "proxy": "",
                "proxy_randomize_credentials": false
            },
            {
                "name": "onion",
                "limited": true,
                "reachable": false,
                "proxy": "",
                "proxy_randomize_credentials": false
            }
        ],
        "relayfee": 0.00001,
        "incrementalfee": 0.00001,
        "localaddresses": [
            {
                "address": "20.8.1.103",
                "port": 8333,
                "score": 1
            }
        ],
        "warnings": ""
        }
    }  

getpeerinfo
========

bitcoin rpc for getpeerinfo.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getpeerinfo

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
    "values": [
        {
            "id": 0,
            "addr": "51.154.60.34:8333",
            "addrlocal": "13.250.189.186:10157",
            "addrbind": "20.8.1.33:51984",
            "services": "000000000000040d",
            "servicesnames": [
                "NETWORK",
                "BLOOM",
                "WITNESS",
                "NETWORK_LIMITED"
            ],
            "relaytxes": true,
            "lastsend": 1603168028,
            "lastrecv": 1603168031,
            "bytessent": 124958917,
            "bytesrecv": 458812896,
            "conntime": 1602037402,
            "timeoffset": 7,
            "pingtime": 0.234671,
            "minping": 0.148192,
            "version": 70015,
            "subver": "/Satoshi:0.18.0/",
            "inbound": false,
            "addnode": false,
            "startingheight": 651584,
            "banscore": 0,
            "synced_headers": 653523,
            "synced_blocks": 653523,
            "inflight": [],
            "whitelisted": false,
            "permissions": [],
            "minfeefilter": 0.00001,
            "bytessent_per_msg": {
                "addr": 236115,
                "feefilter": 32,
                "getaddr": 24,
                "getblocktxn": 725,
                "getdata": 28047333,
                "getheaders": 1053,
                "headers": 50456,
                "inv": 91387979,
                "notfound": 111767,
                "ping": 301408,
                "pong": 301376,
                "sendcmpct": 99,
                "sendheaders": 24,
                "tx": 4520374,
                "verack": 24,
                "version": 128
            },
            "bytesrecv_per_msg": {
                "addr": 209662,
                "blocktxn": 816959,
                "cmpctblock": 17018070,
                "feefilter": 32,
                "getdata": 431988,
                "getheaders": 1053,
                "headers": 45280,
                "inv": 70147264,
                "notfound": 56327,
                "ping": 301376,
                "pong": 301408,
                "reject": 15625,
                "sendcmpct": 66,
                "sendheaders": 24,
                "tx": 369467612,
                "verack": 24,
                "version": 126
            }
        },
        {
            "id": 1,
            "addr": "93.88.75.75:8333",
            "addrlocal": "13.250.189.186:27409",
            "addrbind": "20.8.1.33:55542",
            "services": "000000000000040d",
            "servicesnames": [
                "NETWORK",
                "BLOOM",
                "WITNESS",
                "NETWORK_LIMITED"
            ],
            "relaytxes": true,
            "lastsend": 1603168030,
            "lastrecv": 1603168030,
            "bytessent": 123770795,
            "bytesrecv": 596513702,
            "conntime": 1602037407,
            "timeoffset": 5,
            "pingtime": 0.181661,
            "minping": 0.155844,
            "version": 70015,
            "subver": "/Satoshi:0.16.0/",
            "inbound": false,
            "addnode": false,
            "startingheight": 651582,
            "banscore": 0,
            "synced_headers": 653523,
            "synced_blocks": 653523,
            "inflight": [],
            "whitelisted": false,
            "permissions": [],
            "minfeefilter": 0.00001,
            "bytessent_per_msg": {
                "addr": 239220,
                "block": 1079340,
                "cmpctblock": 192895,
                "feefilter": 32,
                "getaddr": 24,
                "getblocktxn": 4360,
                "getdata": 34222609,
                "getheaders": 1053,
                "headers": 153594,
                "inv": 86655890,
                "notfound": 35328,
                "ping": 301408,
                "pong": 301472,
                "sendcmpct": 198,
                "sendheaders": 24,
                "tx": 583196,
                "verack": 24,
                "version": 128
            },
            "bytesrecv_per_msg": {
                "addr": 188662,
                "blocktxn": 2360809,
                "cmpctblock": 9289483,
                "feefilter": 32,
                "getdata": 78575,
                "getheaders": 1053,
                "headers": 115982,
                "inv": 75128871,
                "notfound": 64996,
                "ping": 301472,
                "pong": 301408,
                "reject": 13508,
                "sendcmpct": 132,
                "sendheaders": 24,
                "tx": 508668545,
                "verack": 24,
                "version": 126
            }
        },
        ]
    } 

listbanned
========

bitcoin rpc for listbanned.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/listbanned

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
    "values": []
    }

ping
========

bitcoin rpc for ping.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/ping

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
    "values": "Operation completed succcessfully"
    }

getutxobyaddress
========

bitcoin rpc for getutxobyaddress.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getutxobyaddress

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
    "address": "n4rZHAPGXCu8bYchjzJhK3V7VVreascJxe"
    }

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": []
    }

getbalancebyaddress
========

bitcoin rpc for getbalancebyaddress.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/getbalancebyaddress

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
    "address": "n4rZHAPGXCu8bYchjzJhK3V7VVreascJxe"
    }  

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": {
        "confirmed": 0,
        "unconfirmed": 0,
        "balance": 0
        }
    }

gettransactionbytxid
========

bitcoin rpc for gettransactionbytxid.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/gettransactionbytxid

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
    "txid": "3df7b98a822746a93b44beec8a7be6aa585da47e763549d48ecc4a666e1ad314"
    }

Response
--------
Returns the current block number::

    {
    "status": ,
    "values": 
    }

gettransactionbyaddress
========

bitcoin rpc for gettransactionbyaddress.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/gettransactionbyaddress

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
    "address": "n4rZHAPGXCu8bYchjzJhK3V7VVreascJxe"
    }

Response
--------
Returns the current block number::

    {
    "status": 200,
    "values": []
    }

createrawtransaction
========

bitcoin rpc for createrawtransaction.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/createrawtransaction

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
        "txin": [
                        {
                            "txid": "",
                            "vout": 0
                        }
                    ],
        "txout": [
                        {
                            "address": "",
                            "amount": 0
                        }
                    ]
    }

Response
--------
Returns the current block number::

    {
    "status": ,
    "values": 
    }

signrawtransactionwithkey
========

bitcoin rpc for signrawtransactionwithkey.

Returns the best block hash::

    http://integrationhub.okwave.asia/api/v2/btcmainnet/signrawtransactionwithkey

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
    "hexstring": "0200000001669576892eb617435059fb6c5976e8bf526149c0f09ce7dcdc4af0ed995b10390000000000ffffffff0150c300000000000017a914f0a454d03ca355e47b13fbdd497d258a0b365b0a8700000000",
    "privkeys": [""]
    }

Response
--------
Returns the current block number::

    {
    "status": ,
    "values": 
    }
