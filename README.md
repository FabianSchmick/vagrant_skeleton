# vagrant_skeleton

Vagrant skeleton including ansible configuration for web development

## Installation

What you need:
- Vagrant (https://www.vagrantup.com/)
- VirtualBox (https://www.virtualbox.org/)
- Terminal (recommend Cygwin: https://www.cygwin.com/)

## Get started
- Open up Vagrantfile
    - Change "PROJECTNAME" to your project name
- Open your terminal and go to the vagrant directory
	- Run "vagrant up"
    - Wait until it's finished
    - Put your public files into the web directory
- Open your browser and open the address "192.168.56.130"

## Useful Vagrant commands
- vagrant up (starts the vagrant machine)
- vagrant ssh (ssh tunnel into the virtual machine)
    - cd /vagrant (brings you to the project root)
- vagrant halt (halts, but doesn't work sometimes)
- vagrant destroy (destroys)
- vagrant status (status)
