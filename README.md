# debian notes

My notes about setting up debian

1) lightdm & i3
2) wicd for wireless
3) disable caps lock permanently in `/etc/default/keyboard`

    XKBMODEL="pc105"
    XKBLAYOUT="us"
    XKBVARIANT="dvorak"
    XKBOPTIONS="ctrl:nocaps"

    BACKSPACE="guess"

4) swap Alt_L Control_L

## optional

1) Install chrome (download, dpkg -i)
2) Add a mapping in ~/.i3/config:

    bindsym $mod+g exec google-chrome

3) Add ssh-agent in your bash profile if you secure all your private keys
   so you don't have to re-enter it everytime you git pull / push, etc etc.

## hardware

TL;DR avoid realtek network cards if you can. Intel is
well supported.

## bonus

get a [mechanical keyboard][das]:


[das]: http://www.amazon.com/Das-Keyboard-Model-Ultimate-Mechanical/dp/B003F7WXTG
