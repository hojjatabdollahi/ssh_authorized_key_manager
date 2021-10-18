# SSH authorized_key Manager
Add/Remove/Enable/Disable authorized_key for ssh.

* Have the public key handy. 
* Call this script with `./authkeys add <username>@<host>`. 
* Paste the public key into the editor.
* You can then see it in the list: `./authkeys list`. 
* Then enable the key `./authkeys enable <username>@<host>`.
