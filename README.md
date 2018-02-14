# Ansible SELF deploy playbook

## Installing

### Install ansible

On Debian/Ubuntu

````bash
$ sudo apt-get install ansible
````

### Clone this playbook

````bash
$ git clone git@github.com:InnovaLangues/self-deploy.git

````

### Make a real file from servers.dist
````bash
$ cp servers.dist servers
$ vi servers
````

### Have the correct SSH keys set up

## Run

````bash
$ ansible-playbook -i servers playbook-prod.yml --ask-sudo-pass
````

(or "preprod" instead of "prod")