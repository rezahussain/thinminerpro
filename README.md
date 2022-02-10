# Thinminerpro
Thinminerpro is a cryptocurrency miner program for MacOS which implements the kawpow hashing algorithm and is written in Swift + Metal<br>
<br>
You can use this with unmineable to mine any cryptocurrency on your Mac<br>
<br>
Ask questions here or in the support thread at https://twitter.com/RezaAliHussain/status/1490443591017275401?s=20&t=9ylxqffK1JF5xpXmLzEjUA

This was compiled on MacOS Catalina 10.15.7 on a 2017 macbook pro, and tested using a Gigabyte AMD Radeon RX 580 egpu. I cannot compile it for Apple Silicon until I get a new macbook pro.

To Use:<br>
1. Download from here if you are running on an intel mac (https://github.com/rezahussain/thinminerpro/releases/tag/2022_02_06) and extract to your desktop<br>
2. Download from here if you are running on an M1 Mac (https://github.com/rezahussain/thinminerpro/releases/download/2022_02_10/thinminerpro_arm.zip)
3. Edit the config.json file to use an unmineable style user eg token:walletaddress.workername<br>
4. Then cd to the directory in Terminal and do ./thinminerpro<br>

This code uses:<br>
https://github.com/jedisct1/swift-sodium<br>
