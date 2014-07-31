Colour Term
===========

Small script (for OS X) that will generate a new terminal background color based on the server hostname your connecting to


Installation
============

* Download cssh.sh
* Make it executable `chmod +x cssh.sh`
* Run `bash cssh.sh 192.168.1.1` or `bash cssh.sh your-hastname.com`

Extras
======
To make things easier and to make the command globally available, follow these steps:
* Run `sudo cp cssh.sh /usr/local/bin`
* Enter your password

To make thing even easier, I prefer to remove the `.sh` extension so I don't have to type it each time
* Run `mv /usr/local/bin/cssh.sh /usr/local/bin/cssh`

Thats is it. Now from anywhere, you should be able to just run `cssh 192.168.1.1` or `cssh your-hastname.com`


* This script was taken from a post on StackExchange, by user [**adamfield**](http://superuser.com/users/63588/adamfield). I'm posting here mainly so I have a record of this very useful script, but also to help others that may need it
