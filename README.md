# Razerstealthlinuxsupport
Since 2018 I have built custom images in linux for every razer stealth model built. This forum will be used for showing others how to get the operating systems running for themselves. Please post comments if any issues are encountered when following the guide 


'sudo su'
'prime-select intel'
perform the above command at boot in order to get to the desktop
apt-get remove --purge nvidia-*
#the above command removes the faulty drivers for the 1650 max q
ubuntu-drivers autoinstall
#this should install the correct drivers
apt-get update && apt-get upgrade 
#the above command should fix an issue with the wireless and bluetooth that occurs at the removal of nvidia
