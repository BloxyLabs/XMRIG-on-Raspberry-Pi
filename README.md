# Installing XMRIG on your Raspberry Pi
**and mine on Unmineable**
<br>
<br>
<br>
<br>
Check also our YouTube channel for instructions and other related information [YouTube](https://www.youtube.com/@bloxylabs "YouTube").
<br>
If you had fun with the projects, please consider buying us a [cup of coffee](https://www.buymeacoffee.com/bloxylabs "cupofcoffee") :coffee:.

<h3><u>The commands to install XMRIG</u></h3>
```
sudo apt update
sudo apt full-upgrade -y
```
<p>sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev -y</p>
<p>git clone https://github.com/xmrig/xmrig.git</p>
<p>cd xmrig</p>
<p>mkdir build</p>
<p>cd build</p>
<p>cmake ..</p>
<p>make</p>
<p>cd</p>
