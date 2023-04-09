# Creating an Account and Accessing the Nautilus Server

Currently, the machine has a single user, `nautilus`.  Eventually, we will add 
more users.    To access the machine, follow the following steps:

*  Generate an ssh key pair.  There are several instructions online.  On
Windows, you can use the following simple
[instructions](https://www.howtogeek.com/762863/how-to-generate-ssh-keys-in-windows-10-and-windows-11/).
In the following, I will assume the key pairs have the filenames, `oai_rsa` for the private key,
and `oai_rsa.pub` for the public key.  
* Send the pulic key to the administrator, who will add the key to the list of authorized keys for the user, `nautilus`.
* On your local machine, you can now login.  For example, in the Windows powershell, you can log in with:
~~~
    ssh nautilus@216.165.12.75 -i .ssh/oai_rsa
~~~
