# freenas_pihole
an attempt was made

#Setup of the jail as follows:
#enable ssh to jail
sysrc sshd_enable="YES"
#start ssh service
service sshd start
#add a user to system for ssh connect, use csh when prompted
adduser
#change root password (uncertain if necessary)
passwd
#install the package installer
pkg install
#install sudo for superuser
pkg install security/sudo
#add [user] to sudo group by adding entry into /usr/local/etc/sudoers
ckoulas ALL=(ALL) ALL
#installed nano, git, 
