# SuperNet-Lite
Use the whole Nxt Client without the need to download the Blockchain. The SuperNET Wallet lets you use your favorite crypto currencies directly on top of the Nxt decentralized Network. Handle your Bitcoin, BitcoinDark, Litecoin, Dogecoin, DASH, Dogecoin, Influx, Opal and Vericoin all easy to setup. No need to use exchanges anymore, trade the currencies directly on the decentalized Nxt Asset Exchange.

![Alt text](/img/snet_lockscreen.png?raw=true "SuperNET Welcome Screen")

![Alt text](/img/coins.png?raw=true "SuperNET Coins Board")

![Alt text](/img/nxt_wallet.png?raw=true "Nxt Welcome Screen")

#How do I get set up?

##Windows

Run the supernet.exe

##Linux


Open a terminal window in the SuperNET Lite folder and start it with ./supernet

##Mac

Open the Terminal in the SuperNET Lite folder and type ./supernet_mac

##Node

Install nodejs

node server.js

Ubuntu

sudo apt-get update

sudo apt-get install nodejs

nodejs server.js

#How to start?

After running the exeuctable you can find the Wallets on:

http://localhost:7110

and

http://localhost:7110/nxt.html

# Possible Bugs

Try to run the executable first and navigate to http://localhost:7110

When this does not work, try to use node as stated above.

When an error  throw err; comes, try to do the node installation as above and then in terminal

node serve.js

(depends how you installed node: nodejs serve.js )

#Security

The SuperNET Lite wallet uses the NRS and Jay framework. The NRS Framework is made from the Nxt developers, who secure that transactions are wrapper with javascript and your passphrase (the passphrase will never leave your browser), before they get sent to the node. You can have your localnode running (install and run Nxt - open CORS), if not, you will connect to a random public node from the Nxt Network. The Jay Framework provides some additional Nxt JavaScript functions that put another layer of security upon the NRS Framework. Jay checks several public nodes against each other to provide the quickest and most responsible node from the Nxt framework.

How to open CORS: https://medium.com/@Damelon/coding-for-nxt-crypto-platform-1-c3580b4cfd38#.7mswh42qu
