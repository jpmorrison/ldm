
2020-01-16 

Code updated to compile and work on x86_64 Linux and Cygwin 
tested on 2TB drives and test images from libldm
see: https://github.com/mdbooth/libldm/blob/master/test/data/ldm-data.tar.xz

Removed ldminfo from test because it has its own repository

https://github.com/flatcap/ldminfo

I have updated ldminfo at https://github.com/jpmorrison/ldminfo


The kernel LDM driver prints some warnings on certain dyanmic (LDM) disks
The errors may be safe to ignore and hopefully ldminfo can help troubleshoot.

I am not an expert in LDM disks but these tools have help with troubleshooting 
Windows dynamic disks. 

John Paul 

ldm@bogomips.com

