# LEMP stack with CentOS 6.5

## The stack

This is a basic LEMP stack using CentOS


## The setup

For the initial ansible package, I've used [Phansible](http://phansible.com/) - and kept its initial folder structure, but changed it to use CentOS instead of Ubuntu.

This dev box it has been configured with the following:

* It uses CentOS 7 (relativkreativ/centos-7-minimal)
* Nginx 1.8
* PHP 7
* MariaDB
* RabbitMQ 3.5.3


## Configuration

The current configuration:

* Mounts current dir to /srv
* IP: 192.168.32.52
* Rabbit: 192.168.32.52:15672

For custom configuration you can edit the `Vagrantfile` as well as `ansible/vars/all.yml`

### Credentials

* Database: root / Admin123
* RabbitMQ: admin / Admin123




