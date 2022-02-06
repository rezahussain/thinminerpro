# Thinminerpro
Thinminerpro is a cryptocurrency miner program for MacOS which implements the kawpow hashing algorithm and is written in Swift + Metal

Ask questions here or in the support thread at https://twitter.com/RezaAliHussain/status/1490443591017275401?s=20&t=9ylxqffK1JF5xpXmLzEjUA

This was compiled on MacOS Catalina 10.15.7 on a 2017 macbook pro, and tested using a Gigabyte AMD Radeon RX 580 egpu. I cannot compile it for Apple Silicon until I get a new macbook pro.

To Use:<br>
1. Download from here (https://github.com/rezahussain/thinminerpro/releases/tag/2022_02_06) and extract to your desktop<br>
2. Edit the config file to use an unmineable style user eg token:walletaddress.workername<br>
3. Then cd to the directory in Terminal and do ./thinminerpro<br>
  
You need a GPU that can fit the kawpow DAG size in it's memory<br>
  
My macbook has 3 devices, I set it to device 1 which is the RX580 egpu, but you should probably set it to 0 to use the default GPU in your computer.<br>
  

This software is not fully ironed out, but I am presenting it to the community to get feedback while I work on it.

This code uses:<br>
https://github.com/jedisct1/swift-sodium<br>
https://github.com/krzyzanowskim/CryptoSwift<br>
