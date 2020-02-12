# uid
print and  examine real and effective uid

Example made from https://linuxconfig.org/how-to-use-special-permissions-the-setuid-setgid-and-sticky-bits

Run the program before and after

sudo chown root setuid

sudo chmod 4755 setuid

and you will see the difference.


You compile the program with 
gcc -o uid sels uid.c
