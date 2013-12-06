[ANN][PAY]Paycoin-PoW/PoS |Transaction Comment|Re-Launch

Version [1.0.1]



[(re)Announcing Paycoin - PAY, the Reawakening.

Paycoin combines Bitcoin/Litecoin/Novacoin/Florincoin/Cosmoscoin features, it uses both Proof of Work and Proof of Stake. This provides good resistance to 51% attacks. It also supports transaction comments like the original Florincoin, so when you send any transactions, you can include the reason for sending, and whatever else you want. Moreover, this coin has very low transaction fees (only 0.1% of most other coins), and fast transaction confirmation time (1.5 min). It provides steady coin supply at 3.5 coins per block.

Paycoin had a fair start and zero premined.

About the Re-Launch:

I (gorgorom) took over the development of this coin for a few reasons.
1. Because I want to extend my knowledge of C programming and its counterparts.
2. Because I really like the name, and believe I can make it go somewhere.
3. To expierement and have a bit of fun in the progress.

I believe any coin deserves a chance to shine. Why the developer made this coin and then abandoned it, I do not know. I want to get this coin promoted, and used for things besides pumping and dumping. I also chose this coin because of the low block reward. This helps to decrease inflation, and will be beneficial in the long term.

Let the reawakening begin.


Features:

- Proof of Work Combined with Proof of Stake
- Transaction comments like FlorinCoin
- Low Transaction Fee (Min Fee is 0.00001 Coins)
- Quick Confirmations
- Resistance to 51% attacks
- Stable Reward Per Block (with the total number of 1 billion and reward 3.5 coins per block, the generation of paycoins stable during more than 270 years)


Specifications:

- Proof of work/proof of stake 
- Scrypt
- 30 seconds block time
- 3.5 coins per block
- Day generation: 10080 coins or 2880 blocks
- 480 blocks retarget (4 hours)
- Trade confirm: 3
- Mine confirm: 30
- Total number of coins 1000000000 (1 billion) 
- fair start, no premine
- port: Connection: 9288 and RPC Port:9289 


Website:
Being worked on.

Blockchain Explorer:
- to be added -


Sample Paycoin.conf:

rpcuser=username
rpcpassword=xxxx
listen=1
daemon=1
server=1
rpcport=9289
rpcconnect=127.0.0.1
maxconnections=200
rpcport=9289
port=9288
addnode=84.200.17.243
addnode=106.186.115.58
addnode=69.147.229.226
addnode=64.251.188.66





Getting Started:

1. Start up paycoin-qt, wait for it to load, then exit.
2. Put paycoin.conf (see sample file above) in your c:/users/**yourcomputername**/Appdata/Roaming/Paycoin
3. restart paycoin-qt, and you should connect and sync.
4. For solo mining, launch cgminer or the mining program you use and begin mining.
      cgminer ex: cgminer.exe --scrypt -o localhost:9289 -u **yourusername** -p **password** (without **)
