Colour Term
===========

Small bash script that will change your terminal colour when connecting to remote computer


Installation
============

* Download cssh.sh
* Make it executable `chmod +x cssh.sh`
* Run `bash cssh.sh 192.168.1.1` or `bash cssh.sh your-hastname.com`

Extras
======
To make things easier and to make the command globally available, follow these steps (your paths may differ, this is for OS X):
* Run `sudo cp cssh.sh /usr/local/bin`
* Enter your password

To make thing even easier, I prefer to remove the `.sh` extension so I don't have to type it each time
* Run `mv /usr/local/bin/cssh.sh /usr/local/bin/cssh`

Thats is it. Now from anywhere, you shoudl be able to just run `cssh 192.168.1.1` or `cssh your-hastname.com`
