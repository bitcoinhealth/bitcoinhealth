## BitcoinHealth Coin

BitcoinHealth Core and Wallets can be installed/configured on MAC. 

#Wallet:

1. Download MAC Wallet Zip file
2. Click on BitcoinHealth.dmg file
3. Add Security exception to allow for wallet file to be installed if prompted.
4. Select folder to install Wallet: “$HOME/Library/Application Support/BitcoinHealth/”.
5. In Terminal go to: “$HOME/Library/Application Support/BitcoinHealth/”. 
6. Create bitcoinhealth.conf:  > touch bitcoinhealth.conf
Paste the following text into bitcoinhealth.conf and save the file.

//Create unique rpcuser name
rpcuser=rpc_bitcoinhealth
//Create unique rpcpassword
rpcpassword=b29dfd951a42a769b0681fcdf
rpcallowip=127.0.0.1
rpcport=17947
listen=1
server=1
addnode=node1.walletbuilders.com
addnode=45.35.13.236
addnode=67.211.45.215

7. Go to Applications > BitcoinHealth Wallet (yellow icon)

8. After connecting to peers (See Help > Debug > Peers)
9. Go Help > Console > Generate 1

#Build from Source:

1. Download BitcoinHealth-source.tar.gz
2. See Unix-Build.md for system install prerequisites
3. A. > ./autogen.sh  B. > ./configure   C. >  make
4. In Terminal go to: “$HOME/Library/Application Support/BitcoinHealth/”. 
6. Create bitcoinhealth.conf:  > touch bitcoinhealth.conf
Paste the following text into bitcoinhealth.conf and save the file.

//Create unique rpcuser name
rpcuser=rpc_bitcoinhealth
//Create unique rpcpassword
rpcpassword=b29dfd951a42a769b0681fcdf
rpcallowip=127.0.0.1
rpcport=17947
listen=1
server=1
addnode=node1.walletbuilders.com
addnode=45.35.13.236
addnode=67.211.45.215

7. In src folder execute: CLI: >  ./bitcoinhealthd  and for GUI > src/qt bitcoinhealth-qt 
