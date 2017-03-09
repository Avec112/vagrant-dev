# vagrant-dev
Vagrant file for creating java 8 development environment.

Base box geerlingguy/ubuntu1604 v1.0.9 (Ubuntu Server 16.04.2 LTS)

## Provisioning

Installs the following
* docker-ce (currently v17.03)
* ansible (currently v2.2.1.0)
* openjdk-8-jdk (currently v1.8.0_121)
* maven (currently v3.3.9)


## Requirments
* Virtualbox v5.1.x or newer is recommended. No older than 4.0.x (only tested 5.1.x )
* Vagrant v1.9.2 or newer. (1.9.1 og older might work, but then you must change Vagrant.require_version first)

## Commands
* Start with `vagrant up`
* Login with `vagrant ssh`
