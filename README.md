# gatech-omscs-cs6265
Cs6265 @ gatech 

## lab hacks
All of the writeups here will crack the gatech cs6265 labs without *actually* solving most of the challenges.
Consider this a responsible disclosure.

### lab 01 - CTF
Simply run the python file on the provided Vm to get your hahses.  Don't forget to alter the gatech id variable to b uour now


### lab 02 -- log4j
This one fun.  
Shut down the VM. 
Clone the disk in vbox.  
Make a new VM of any debian or Ubuntu distro and attach the cloned vbox disk.  Start the new VM, mount the disk, chroot into it, and give sudo group membership to cs6256 and log4j users (pwnd).
Now, [Todo]
