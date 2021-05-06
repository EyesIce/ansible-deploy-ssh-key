# ansible-deploy-ssh-key
Use this script ansible to deploy ssh public key of multiple user in multi host. The inventory in set to work with a Bastion Host and several Target Host in private network.


- create a folder in main project and call it ssh_public
- add the public keys in the folder and name those like: user.pub
- change iventory variable
