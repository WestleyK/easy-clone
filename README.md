## A simple script to make it easier when cloning repos.

<br>
<br>


## Install:

<br>

### Quick and easy install:

Copy-paste or type this in your terminal:
```
curl https://raw.githubusercontent.com/WestleyK/easy-clone/master/easy-install.sh | sh
sudo mv hubget /usr/local/bin/
source ~/.bashrc
```

<br>

Then to test it, type:
```
hubget <TAB> <TAB>
```
You should see some stuff like:
```
WestleyK/arduino-key-pad         WestleyK/drive-speed-test        WestleyK/pi-backlight            golang/dep
WestleyK/drive-mount             WestleyK/easy-clone              WestleyK/rpi-brightness          WestleyK/ssh-watcher
WestleyK/drive-mounting-script   WestleyK/install-script
```

If you don't, close and then reopen the terminal and it should work now.
If it still doesn't work, then please open an issue.

<br>
<br>

### Install by cloning repo:

```
cd ~/
git clone https://github.com/WestleyK/easy-clone.git
cd easy-clone/
./make.sh
sudo ./make.sh install
source ~/.bashrc
```
<br>

## Usage:

And now you can clone a repo much easier. <br>
Here's a example: <br>

```
hubget WestleyK/rpi-brightness
```
See? It's pretty simple! <br>
When you want to clone it again, just use TAB: <br>

```
hubget WestleyK/rp <TAB>
hubget WestleyK/rpi-brightness
```

<br>
<br>


### better README comming soon


<br>
<br>

### End README


<br>
<br>



