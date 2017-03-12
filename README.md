Node-Red Vagrant machine
========================

Quick setup of Node-Red with a Vagrant machine.

## Setup

### Requirements (host environment)

- Vagrant
- Ansible

### Instructions

1. Clone this repository
2. CD into this repository's root directory
3. run `vagrant up`
4. ssh into the VM with `vagrant ssh`
5. Run `node-red` on the VM (TODO: make node-red a service)
6. On your host machine, open a web browser and go to `http://localhost:1880`
