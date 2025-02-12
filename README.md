# GRUB-RESCUE
Boot loder error
Commands 
Ls #first list all the disks
set prefix=(hd0,msdosX # type the locationof the disk )/boot/grub  
set root=(hd0,msdosX)  
insmod normal  
normal
