# GRUB-RESCUE
Boot loder error
Commands 
Ls #first list all the disks
set prefix=(hd0,gpt(and the number) # type the locationof the disk )/boot/grub  
set root=(hd0,gpt)  
insmod normal  
normal

after geting into the os thype this 
sudo grub-install /dev/sdX
sudo update-grub

