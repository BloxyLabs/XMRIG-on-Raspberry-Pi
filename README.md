# Installing XMRIG on your Raspberry Pi
**and mine on Unmineable**
<br>
Check also our YouTube channel for instructions and other related information [YouTube](https://www.youtube.com/@bloxylabs "YouTube").
<br>
If you had fun with the projects, please consider buying us a [cup of coffee](https://www.buymeacoffee.com/bloxylabs "cupofcoffee") :coffee:.

<h3><u>The commands to install XMRIG</u></h3>

```
sudo apt update
sudo apt full-upgrade -y
sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev -y
git clone https://github.com/xmrig/xmrig.git
cd xmrig
mkdir build
cd build
cmake ..
make
cd
```
<br>
<h3><u>The commandline to start mining on Unmineanle</u></h3>

./xmrig -o rx-eu.unmineable.com:3333 -u <COIN>:<Wallet Address>.<RIG Name>#<Referal Code> -p x
Example from video
./xmrig -o rx-eu.unmineable.com:3333 -u XNO:<Wallet Address>.PI5#Bloxy-Labs -p x
