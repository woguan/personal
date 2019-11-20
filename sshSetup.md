Creating SSH:

ssh-keygen -t rsa<BR>
After firing above command, it will prompt you to choose a location to have the SSH files to be saved. Choosing default location is recommended.

Once you choose the location, it will ask you to type a passphrase. No passphrase is allowed, but not recommended.

Optional: 

To avoid the system to keep asking for the SSH keys credentials for ALL hosts:

Create a new file 'config' in the .ssh
in the config file: 

Host *
 UseKeychain yes


Notes:

-t : Specifies the type of key to create.

rsa : Rivest-Shamir-Adleman, encrypting/decrypting algorithm
