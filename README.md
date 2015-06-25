#Ansible SELF deploy playbook

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

### Make a production file from production.dist
````bash
$ cp production.dist production
$ vi production
````

### Have the correct SSH keys set up

## Run

````bash
$ ansible-playbook -i production self.yml --ask-sudo-pass
````