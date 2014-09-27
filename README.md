Fix-Intel-backlight-on-LInux-Asus-eeepc
=======================================

Instructions to fix hotkeys not working


- wget https://github.com/enricocid/Fix-Intel-backlight-on-LInux-Asus-eeepc/blob/master/20-intel.conf

- wget https://github.com/enricocid/Fix-Intel-backlight-on-LInux-Asus-eeepc/blob/master/glamor.conf

- sudo cp 20-intel.conf glamor.conf /etc/X11/xorg.conf.d/

- restart the session



**nOTE: If xorg.conf.d folder doesn't exist, create it :)**

sudo mkdir /etc/X11/xorg.conf.d 
