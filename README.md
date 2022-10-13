# Razerstealthlinuxsupport
Since 2018 I have built custom images in linux for every razer stealth model built. This forum will be used for showing others how to get the operating systems running for themselves. Please post comments if any issues are encountered when following the guide 

```bash
sudo su
prime-select intel
apt-get remove --purge nvidia-*
ubuntu-drivers autoinstall
apt-get update && apt-get upgrade 
