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
$ ansible-playbook -i infra-linode playbook-prod.yml --ask-sudo-pass
````

You can replace "**linode**" by : **gricad-uga**

You can replace "**prod**" by : **preprod**

