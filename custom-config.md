## Show flags instead of labels in the keyboard layout language indicator in GNOME shell on Ubuntu 18.04 


sudo -i gedit /usr/share/X11/xkb/rules/evdev.xml 
find and replace 
#### for 🇬🇧 
`<shortDescription>en</shortDescription>` to `<shortDescription>🇬🇧</shortDescription>` 
#### for 🇺🇦 
`<shortDescription>uk</shortDescription>`to `<shortDescription>🇺🇦</shortDescription>`

save and reboot 


## Cockpit on Ubuntu 18.04
Cockpit provides web interface for managing Linux Distributions via a Web Browser 

sudo apt-get install cockpit
sudo systemctl start cockpit

https://ip-address-of-machine:9090
