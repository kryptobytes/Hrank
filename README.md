Hrank (TRR)

Hrank was generated by Kryptobytes.

Launch your coin
================

You will need to create the first seed nodes of your coin.  In order to do this you will need two servers with different IP's.

If you are on a linux server just run the launchCoin.sh file on each server with the appropriate variables like this:

On 1st server run: 
		
./launchCoin.sh Hrank rpcPort ipServer2

On 2nd server run: 

./launchCoin.sh Hrank rpcPort ipServer1


test successful if when run:
		./Hrankd getinfo

You should get a return like:

{
     "version": 100000,
     "protocolversion" : 60001,
     "walletversion" : 60000,
     "balance" : 0.00000000,
     "blocks" : 0,
     "connections" : 1,
     "proxy" : "",
     "difficulty" : 0.00024414,
     "testnet" : false,
     "keypoololdest" : 1376825739,
     "keypoolsize" : 101,
     "paytxfee" : 0.00000000,
     "mininput" : 0.00010000,
     "errors" : ""
}


