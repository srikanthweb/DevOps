# Installation of Ansible on Ubuntu
Ubuntu builds are available in a [PPA here](https://launchpad.net/~ansible/+archive/ubuntu/ansible).

To configure the PPA on your machine and install Ansible run these commands:
~~~sh
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo add-apt-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
~~~

### Install On Other Platforms
* [Install on Debian](../Ansible_installation/Installation_Ansible_on_Debian.md)
* [Install on Redhat, CentOS and Fedora](../Ansible_installation/Installation_Ansible_on_Redhat_CentOS_Fedora.md)
