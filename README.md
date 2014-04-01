# Deploy with Capistrano to a multi-machine Vagrant environment

## Installation

Download Vagrant http://www.vagrantup.com/

### Download the box and run the VM

    vagrant up

### Acces the VM using SSH

    vagrant ssh vm1

    vagrant ssh-config vm1 >> ~/.ssh/config
    ssh vm1

# Capistrano usage

    $ bundle exec cap install
    $ bundle exec cap production deploy

# Documentation

http://docs.vagrantup.com/
https://github.com/capistrano/capistrano/blob/master/README.md
