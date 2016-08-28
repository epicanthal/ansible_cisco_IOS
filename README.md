# ansible_cisco_IOS
##Basic Ansible playbooks for Cisco IOS
This project is a collection of playbook examples for networking devices, specifically Cisco IOS.  I only have access to Cisco IOS and NXOS devices so I figured I'd start learning Ansible through interaction with Cisco IOS.

My goal:
- add to this repo as I learn more Ansible.
- enhance my learning by documenting the playbooks
- provide simple examples that aren't too lengthy to hopefully save you time getting started with Ansible w/networking gear.

The idea is to create sections (directories) that are somehow related, e.g. section **_1-cisco_ios_** contains simple playbooks that do not reference any of the Ansible subdirectory structure or roles.

##Section 1-cisco_ios
These playbooks are basic starters that show how to initially get Ansible to talk to Cisco IOS devices (e.g. _connection: local_) and run basic _show_ commands.  Each playbook 1.0 -> 1.x builds on previous playbooks and comments are removed for parts documented in previous playsbooks, while any new material is commented where necessary.

##Notes/Suggestios:
- Get [Ansible](http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-apt-ubuntu) up and running on a Linux/Unix virtual machine.  I'm using [Virtualbox](https://www.virtualbox.org/wiki/Downloads) and [Ubuntu Server 16.04](http://www.ubuntu.com/download/server) on a Macbook...works great
```
$ lsb_release -a
No LSB modules are available.
Distributor ID:	Ubuntu
Description:	Ubuntu 16.04.1 LTS
Release:	16.04
Codename:	xenial

$ ansible --version
ansible 2.1.1.0
  config file = /etc/ansible/ansible.cfg
  configured module search path = Default w/o overrides
```
