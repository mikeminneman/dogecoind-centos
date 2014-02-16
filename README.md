Hello, this is a couple of files to help you get dogecoind running on CentOS
Basically you'll create a new user, and then put these files into the user's
home directory. You don't want to do this as root. Then go ahead and run the
./centos-install.sh and it should create dogecoind, if you've installed
the other yum dependencies. Only other thing to note is that you might need
to after installing make a symbolic link for ld64 in your /lib directory and
you'll need to be root to do that.

Any questions just email me mjm703@gmail.com
If you found this useful, my doge address is D8dgPErq28rDWxCMts2aRb1R9S3gRAx3uA
