# Thinminerpro
Thinminerpro is a cryptocurrency miner program for MacOS which implements the kawpow hashing algorithm and is written in Swift + Metal<br>
<br>
You can use this with unmineable to mine any cryptocurrency on your Mac<br>

If you are completely new to crypto mining, read this post first(https://rezaalihussain.substack.com/p/mining-cryptocurrency-on-mac-os-using?s=w)
<br>
<br>
Ask questions here or in the support thread at https://twitter.com/RezaAliHussain/status/1490443591017275401?s=20&t=9ylxqffK1JF5xpXmLzEjUA

To Use:<br>
1. Download from here if you are running on an intel mac (https://github.com/rezahussain/thinminerpro/releases/download/2022_02_20_intel/thinminerpro_intel.zip) and extract to your desktop<br>
2. Download from here if you are running on an Apple Silicon(eg M1, M1 Pro, M1 Max, M1 Ultra) Mac (https://github.com/rezahussain/thinminerpro/releases/download/2022_03_12_arm_release/2022_03_12_arm_release.zip) and extract to your desktop<br>
3. Edit the config.json file to use an unmineable style user eg token:walletaddress.workername<br>
4. Then cd to the directory in Terminal and do ./thinminerpro<br>

This code uses:<br>
https://github.com/jedisct1/swift-sodium<br>

Like other miners this miner also implements a 1% donation fee.<br>
The Intel build I only tested to work with my RX580 egpu, so I am not sure if it works on other intel macs or not.
