# Change keyboard layout to flags on Ubuntu 18.04 


sudo -i gedit /usr/share/X11/xkb/rules/evdev.xml 
find and replace <br>
#### for 🇬🇧 <br>
`<shortDescription>en</shortDescription>` to `<shortDescription>🇬🇧</shortDescription>` <br>
#### for 🇺🇦 <br>
`<shortDescription>uk</shortDescription>`to `<shortDescription>🇺🇦</shortDescription>`<br>
save and reboot 
