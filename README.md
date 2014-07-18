
Bitstar - BITS

ports:
connection:	62123
RPC:			63124

THIS UPDATE IS MANDATORY

New version of wallet is 1.2.0.0, protocol code 60010

Please update before block 185,000

* added checkpoints
* configured synchronized checkpoints to offer some additional chain protection
* added commandline switches -nostaking and -nolog, primarily to be used by exchanges
* added modifier interval patch, from 8h to 1 minute. Entry at block 185,000
* added address balance column on receive addresses tab
* added anonymous send
* few color changes by changing some in-code stylesheets


* UPDATE ALERTS FOR WALLETS WILL BE PUSHED OUT ON FRIDAY 18 juli 2014

note that qt folder ( containing anonymous send, balance column, and additional services tabs, changed stylesheets ) has not been updated. the qt folder is not needed in order to run a succesfull node/client

this is mainly a release to fix some issues in the previous wallet.

planned is an alternative way of anonymous send, migration to decentralized one.
planned and almost ready is a services tab with various goodies and will be released as a non-mandatory update

* issue with newest release

  sorting on balance on receive page sorts like string - will be fixed in next non-mandatory update
  
  protocol min level fix. this coin has been forked from a non-correct coin when it comes to checking for min proto version. we had to do an ugly fix to disconnect all 60008 clients. we will fix this in a next release.

we are looking at other things we can do and store in the blockchain and preparing the alerts code for something else ;)

.. more to come ..

2 commits in this release:

https://github.com/bitstar/bitstar/commit/f42984fe1c9c4010f0ff93f77eb530b472ae72f7
https://github.com/bitstar/bitstar/commit/0c15bcbc2e083d482230f3b66f6ac7fff5c009b8
