# Installing XMRIG on your Raspberry Pi
**and mine on Unmineable**
<br>
<br>
Check also our YouTube channel for instructions and other related information [YouTube](https://www.youtube.com/@bloxylabs "YouTube").
<br>
If you had fun with the projects, please consider buying us a [cup of coffee](https://www.buymeacoffee.com/bloxylabs "cupofcoffee") :coffee:.

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

**Example from video:**

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

<h3><u>screen commands</u></h3>
<p>screen => to start new screen session</p>
<p>ctrl-a and d => to leave screen session and keep it running</p>
<p>screen -r => to reconnect to the screen session</p>

