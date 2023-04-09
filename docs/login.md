# Creating an Account and Accessing the Nautilus Server

Currently, the machine has a single user, `nautilus`.  Eventually, we will add 
more users.    To access the machine, follow the following steps:

*  Generate an ssh key pair.  There are several instructions online.  On
Windows, you can use the following simple
[instructions](https://www.howtogeek.com/762863/how-to-generate-ssh-keys-in-windows-10-and-windows-11/).
* Send the key to the administrator
* To log in, 
~~~
    ssh nautilus@216.165.12.75 -i .ssh/oai_rsa
~~~
