# ZBank_Blockchain
ZBank Test Blockchain.

Initialize mining nodes:
alphanode
'enode://97274ecf24a9a6711a22f6583e5c15b9a5b62e85138c674baa31191d7c215c0b50a8bdeb6aba2d255005ec05b03101e242de9092c9eea7415bc2789db701a712@127.0.0.1:30303'
betanode 
./geth --datadir betanode --unlock "0x046fE217e2680640AF0CCA097e32C8384C797003" --mine --port 30304 --bootnodes "enode://97274ecf24a9a6711a22f6583e5c15b9a5b62e85138c674baa31191d7c215c0b50a8bdeb6aba2d255005ec05b03101e242de9092c9eea7415bc2789db701a712@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock

Chain ID:
  909
  
Connect to MyCrypto app:

Sign in to existing wallet or generate new 'Wallet' and save mnemonic phrase.

Change Network to 'zbanknet'.

Use Keystore file: select keystore file located C:\ZBank_Blockchain\alphanode\keystore

Choose address to send test ETH. 
