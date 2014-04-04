This is a thoertical coin that was used in the creation of ccoin. I have begun work on it again to simply show some friends how easy it is to make a coin that is 100% premined. This coin runs off of the foocoin and barcoin examples.

Technically you could set the premine rate to whatever you want it to be. For now up to nHeight block 2 there are 700M coins per block. Within the first 10 blocks you should stop mining the coin, get the latest block's hash, and update your checkpoints so someone can't go back and get all those premined coins your greedy little fingers got a hold of.

Contact me if you need a testnet for this code. Please be aware that this genesis block is considered to be "used" and if you some how happen to connect to another node with the same coin you will likely get your chain screwed up


I will be making a sha256D example along with a merged sha256 example the summer of 2014

Written by Joeswhite(majority) and Beastlymac

config example

Shoecoin (HOE)

rpcport= 44222

p2pport= 44223

testnetport=44333



rpcuser=shoecoinrpc

rpcpassword=BuZaDmsiH9qRqmkKkgq9hwxhvR7PRaxntLTQgVcR17xq

addnode= none

rpcport=44222

server=1

daemon=1
