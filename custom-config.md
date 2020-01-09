Change keyboard layout to flags on Ubuntu 18.04 

sudo -i gedit /usr/share/X11/xkb/rules/evdev.xml 
find and replace 
for Eng 
<shortDescription>en</shortDescription> to <shortDescription>🇬🇧</shortDescription> <br>
for UA 
<shortDescription>uk</shortDescription> to <shortDescription>🇺🇦</shortDescription> <br>
save and reboot 
