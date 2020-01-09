# Change keyboard layout to flags on Ubuntu 18.04 


sudo -i gedit /usr/share/X11/xkb/rules/evdev.xml 
find and replace 
#### for 🇬🇧 
`<shortDescription>en</shortDescription>` to `<shortDescription>🇬🇧</shortDescription>` 
#### for 🇺🇦 
`<shortDescription>uk</shortDescription>`to `<shortDescription>🇺🇦</shortDescription>`

save and reboot 
