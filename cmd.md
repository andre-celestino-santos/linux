# user and groups

```bash
# show all users
cat /etc/passwd
# show all groups
car /etc/group
```

sudo adduser <username> = create user
sudo userdel <username> = delete user
sudo passwd <username> = change password
sudo login <username> = login with it
logout
sudo addgroup <groupname> = create group
sudo delgroup <groupname> = delete group
sudo adduser <username> <groupname>
groups <username> = print groups username.

r = read
w = write
x = execute

4+2+1
rwx = 7 (read, write and execute)

4+0+1
r-x = 5 (read and execute)

4+0+0
r-- = 4 (read)

0+0+0
--- = (none)

own group all   own    group
rwx rwx   rwx   andre  andre

sudo chmod 700 <folder/file> uses -R for recursive = change previleges of folder/file.
sudo chown <username> <folder/file> uses -R for recursive = change the own of folder/file.
sudo chgrp <usergroup> <folder/file> uses -R for recursive = change the group of folder/file.


-- package management
sudo apt list --installed | grep docker = print all package contains docker name.
sudo snap list

unzip files
tar -xzf <yourfile>



























