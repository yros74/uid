# uid
print and  examine real and effective uid

Example made from https://linuxconfig.org/how-to-use-special-permissions-the-setuid-setgid-and-sticky-bits

Run the program before and after

sudo chown root uid

sudo chmod 4755 uid

and you will see the difference.


You compile the program with 
gcc -o uid  uid.c
