#DREWGRIF'S I3 SCRIPT
# i3gaps
# Works great with Debian Stable
I wanted to install i3 gaps on debian stable.
My recommendation is to install debian stable minimal (no gui).
I used the expert method.

```
sudo apt install git

git clone https://github.com/drewgrif/i3gaps-debian

cd i3gaps-debian

./install.sh (includes nerdfonts.sh and copyconf.sh unless commented)
```

OPTIONAL:
Nerd Fonts installed by default but can be commented out of install.sh
```
# source ~/i3gaps-debian/nerdfonts.sh
```
OPTIONAL:
Customized configuration installed by default but can be commented out of install.sh
```
# source ~/i3gaps-debian/copyconf.sh
```
NOT OPTIONAL
```
sudo reboot
```

Debian Stable Minimal Install https://www.youtube.com/watch?v=Seqx3Oj5JRE
How to use this github.com https://www.youtube.com/watch?v=npc4-jp_wvs

## This is the look after using: install.sh, nerdfonts.sh, and copyconf.sh

![Debian with i3gaps](https://raw.githubusercontent.com/drewgrif/blog/main/2022-05-18_17-54.png)
