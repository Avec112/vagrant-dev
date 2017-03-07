# vagrant-dev
Vagrant file for creating java 8 development environment.

Base box ubuntu/xenial64 (Ubuntu Server 16.04.2 LTS)

## Provisioning

Installs the following
* docker-ce (currently v17.03)
* openjdk-8-jdk
* maven (currently v3.3.9)

Configurations
* add group docker
* add user to group docker...so you can drop sudo all the time
* copy ~/.gitconfig from host so you have git allready configured

## Requirments
* Provider installed (I like Virtualbox)
* Vagrant installed

## Commands
* Start with `vagrant up`
* Login with `vagrant ssh`
