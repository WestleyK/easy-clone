## Simple script to make it easier when cloning repos

<br>
<br>


## Install:

```
cd ~/
git clone https://github.com/WestleyK/easy-clone.git
cd easy-clone/
sudo ./install.sh
source ~/.bashrc
```

<br>

Then to test it, type:
```
hubget <TAB> <TAB>
```
And you should see some stuff like:
```
WestleyK/arduino-key-pad         WestleyK/drive-speed-test        WestleyK/pi-backlight            golang/dep
WestleyK/drive-mount             WestleyK/easy-clone              WestleyK/rpi-brightness          WestleyK/ssh-watcher
WestleyK/drive-mounting-script   WestleyK/install-script
```

If you don't, then try to close then reopen the terminal and it should work now.
If it still doesn't work, then please open an issue.

<br>
<br>

## Usage:

And now you can clone repo much easier. <br>
Heres a example: <br>

```
hubget WestleyK/rpi-brightness
```
See, pretty simple. <br>
But now when you want to clone it again, just use TAB: <br>

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



