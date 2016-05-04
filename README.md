vagrant-ansible-mongo
=====================

A simple setup for creating a Vagrant box running a
single-instance MongoDB server that gets provisioned
by Ansible.

Although the MongoDB instance runs in a virtual
machine, the guest's port 27017 is forwarded to the
host's port 27017, so you will be able to connect
to the MongoDB server from your host machine
and from its network(s).

#### Requirements:
* Vagrant
* Ansible
* MongoDB client (optional)

#### Quick start:
    git clone https://github.com/lee51/vagrant-ansible-mongo.git
    cd vagrant-ansible-mongo
    vagrant up
    mongo --host localhost --port 27017

#### Reference:
Adam Brett's [_Vagrant & Ansible Quickstart Tutorial_](https://adamcod.es/2014/09/23/vagrant-ansible-quickstart-tutorial.html)

