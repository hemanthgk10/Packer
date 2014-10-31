Packer
======

Packer template files (JSON)  to create Vagrant boxes.

Templates
===========
1. virtual-vm-box.json  - Template to create a VM on virtual box and package it into .box.
2. vmware-vm-box.json   - Template to create a VM on VMware Fusion and package it into .box.

Scripts
==========
1. sshd.sh      -  Script to activate ssh in VM
2. vagrant.sh   -  Script to set up vagrant user to follow the steps in the link.
https://blog.engineyard.com/2014/building-a-vagrant-box
3. vmtools.sh   -  Script to install vmtools in the VM.
