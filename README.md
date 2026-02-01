# Installing XMRig on your Pi


Check also our [YouTube](https://www.youtube.com/@bloxylabs "YouTube") channel for instructions and other related information.

If you had fun with the projects, please consider giving us a Super Thanks on YouTube or buying us a [cup of coffee](https://www.buymeacoffee.com/bloxylabs "cupofcoffee") ☕.

<h3><u>The commands to install XMRIG</u></h3>

```
sudo apt update
sudo apt full-upgrade -y
sudo apt-get install screen
sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev -y
git clone https://github.com/xmrig/xmrig.git
cd xmrig
mkdir build
cd build
cmake ..
make

screen
```

<h3><u>The commandline to start mining on Unmineable</u></h3>

<p>./xmrig -o RANDOMXPOOLSERVER:PORT -u COIN:WALLETADDRESS.WORKERNAME#REFERRALCODE -p x</p>

**Example from Unmineable video:**

<p>./xmrig -o rx-eu.unmineable.com:3333 -u XNO:WALLETADDRESS.PI5#Bloxy-Labs -p x</p>

**Other pool servers:**

<p>Global: rx.unmineable.com:3333</p>
<p>Europe: rx-eu.unmineable.com:3333</p>
<p>United States: rx-us.unmineable.com:3333</p>
<p>Asia: rx-asia.unmineable.com:3333</p>

<h3><u>Referral code</u></h3>
To get a small discount on the UnMineable mining fees use the referral code:

**Bloxy-Labs**
It will reduce your mining fee from 1% to 0.75% and you will also support our YT channel ;)

<h3><u>The commandline to start mining Zephyr on MiningOcean</u></h3>

<p>./xmrig -o POOLSERVER:PORT -u WALLETADDRESS -p x</p>

**Example from Zephyr video:**

<p>./xmrig -o de-zephyr.miningocean.org:5332 -u WALLETADDRESS -p x</p>

<h3><u>The commandline to start mining Salvium on HeroMiners</u></h3>

<p>./xmrig -o POOLSERVER:PORT -u YOUR_SAL_WALLET_ADDRESS -p YOUR_WORKER_NAME -a rx/0 -k</p>

**Example from Salvium video:**

<p>./xmrig -o de.salvium.herominers.com:1230 -u YOUR_SAL_WALLET_ADDRESS -p YOUR_WORKER_NAME -a rx/0 -k</p>

**Example from Etica Protocol video:**

<p>./xmrig -o eticapool.com:3333 -u YOUR_ETICA_WALLET_ADDRESS -p YOUR_WORKER_NAME -a rx/0 -k</p>

<h3><u>The commandline to start mining on HashVault</u></h3>

**Rapberry Pi 5:**
<br>
./xmrig --url pool.hashvault.pro:443 --user YOURWALLETADDRESS --pass RPI --tls --tls-fingerprint 420c7850e09b7c0bdcf748a7da9eb3647daf8515718f36d9ccfdd6b9ff834b14 --randomx-no-numa

**Orange Pi 5:**
<br>
./xmrig --url pool.hashvault.pro:443 --user YOURWALLETADDRESS --pass RPI --tls --tls-fingerprint 420c7850e09b7c0bdcf748a7da9eb3647daf8515718f36d9ccfdd6b9ff834b14

<h3><u>screen commands</u></h3>
<p>screen => to start new screen session</p>
<p>ctrl-a and d => to leave screen session and keep it running</p>
<p>screen -r => to reconnect to the screen session</p>

<h3><u>If you like mining Bitcoin at home</u></h3>
Interested in mining Bitcoin at home with small miners or just looking for cool Bitcoin merchandise? Check out BitcoinMerch.com. You will get a 5% discount by using the code BloxyLabs. Visit their website by clicking the banner below to support the channel.

[![Alt text](bitcoinmergebanner.jpg)](https://bitcoinmerch.com?aff=706)
