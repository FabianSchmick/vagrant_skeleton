# vagrant_skeleton

Vagrant skeleton including ansible configuration for web development

## Installation

What you need:
- VirtualBox (https://www.virtualbox.org/)
- Vagrant (https://www.vagrantup.com/)
- Terminal (recommend Cygwin: https://www.cygwin.com/)

## Get started
- Open up Vagrantfile
    - Change "PROJECTNAME" to your project name
- Open your terminal and go to the vagrant directory
	- Run "vagrant up"
    - Wait until it's finished
    - Put your public files into the web directory
- Go to your operating systems hosts file (e. g. Win7: C:\Windows\System32\drivers\etc)
    - Write an entry like: 192.168.56.128 	local.projectname.com
- Open local.projectname.com in your browser

## Useful Vagrant commands
- vagrant up (starts the vagrant machine)
- vagrant ssh (ssh tunnel into the virtual machine)
    - cd /vagrant (brings you to the project root)
- vagrant halt (halts, but doesn't work sometimes)
- vagrant destroy (destroys)
- vagrant status (status)

## Available roles
Choose your roles in ansible/playbook.yml

- apache-fpm
- app
- composer
- dotfiles
- init
- mailhog
- mysql
- nginx
- ngrok
- nodejs
- php5.6-fpm
- php7.0-fpm
- php7.1-fpm
- ruby
