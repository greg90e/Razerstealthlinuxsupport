# Razer Stealth Video Driver Issue Fix
Since 2018 I have built custom images in linux for every razer stealth model built. This forum will be used for showing others how to get the operating systems running for themselves. Please post comments if any issues are encountered when following the guide 

```bash
sudo su
prime-select intel
apt-get remove --purge nvidia-*
ubuntu-drivers autoinstall
apt-get update && apt-get upgrade 
```
The above commands will fix a known issue with linux pulling the wrong graphics driver as of ubuntu 21.04 at install. In addition the default wireless card is not compatible with linux. I replaced it with a intel 8265
To setup the EGPU you will need to go to https://github.com/hertg/egpu-switcher in order to get that working.
