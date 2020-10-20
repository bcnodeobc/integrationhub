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

bitcoin rpc for uptime .

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
