#### Start A Windows EC2 Instance based on AMI

A Windows AMI (AMI ID: ami-ed82fcd7) has been baked with VirtualBox, Vagrant and Packer.


#### SSH Timeout Issues

Add *private_key_path* to Vagrantfile.

```bash
 # SSH Agent Forwarding
 #
 # Enable agent forwarding on vagrant ssh commands. This allows you to use ssh keys
 # on your host machine inside the guest. See the manual for `ssh-add`.
 config.ssh.private_key_path = '~/.ssh/id_rsa'
 config.ssh.forward_agent = true
```

https://github.com/Varying-Vagrant-Vagrants/VVV/issues/375



