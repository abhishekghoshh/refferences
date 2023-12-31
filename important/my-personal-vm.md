

### All Steps for creating my personalised VM
- Create the VM from ubuntu image [[linux]]
- Share git keys with the vm if you are sharing the git folders in the vm shared volume
	```
	scp ~/.ssh/id_ed25519_personal* abhishek@homelab:/home/abhishek/.ssh/
	sudo su
	sudo chown -R abhishek /media/shared
	```