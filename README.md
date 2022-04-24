# WAR - WebOS Ad Removal (Version 1.00)
### Removes ads from WebOS home screen

**WARNING!** This script is provided with no warranty, use at your own risk. 
I have done the best I can to ensure the changes are safe and that they are not permanent.
To neutralize this script, simply remove the USB and reboot the TV.

This is the first release of this script, as such it is considered to be a testing release. Currently I am only removing the AI recommendations
and the Trending section. There are more sections beneath the App list that I have had success in removing.

## Compatibility
I have tested this on an LG OLED C1 65 inch television with WebOS version: webOS TV 6.2.1
This may work on earlier versions, and it is assumed to be safe to try as the files are checksummed before they are modified. 
Let me know if it works on your device.

## Installation
1. You must root your TV following the instructions provided: https://github.com/RootMyTV/RootMyTV.github.io
2. Setup SSH access using instructions provided by the rootmytv project. I recommend setting up SSH key access.
3. connect to tv by SSH and run command below:
```
curl -L https://raw.githubusercontent.com/nnmdd/war-webos-ad-remover_local/main/webos_ad_remover_local | sh -
```


## Further Notes
There is a lot of potential to customize the home screen further. It looks possible to set back ground images, change colors, and more. 

## Contribute
Code contributions are welcome, as well as bitcoin donations:
bc1qnpvc8yp7tprewaam4v64ga8v0rhnyt67532tk5
![Bitcoin](https://i.imgur.com/Ixe1at6.jpg)
