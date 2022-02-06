# thinminerpro
Thinminerpro is a cryptocurrency miner program for MacOS which implements the kawpow hashing algorithm and is written in Swift + Metal

Ask questions here or in the support thread at https://twitter.com/RezaAliHussain/status/1490443591017275401?s=20&t=9ylxqffK1JF5xpXmLzEjUA

This was compiled on MacOS Catalina 10.15.7 on a 2017 macbook pro, and tested using a Gigabyte AMD Radeon RX 580 egpu. I cannot compile it for Apple Silicon until I get a new macbook pro.

To Use:
  Download and extract to your desktop
  edit the config file to use an unmineable style "user" eg token:walletaddress.workername
  Then cd to the directory in Terminal and do ./thinminerpro

This software is not fully ironed out, but I am presenting it to the community to get feedback while I progress work on it.

This code uses:
https://github.com/jedisct1/swift-sodium
https://github.com/krzyzanowskim/CryptoSwift
