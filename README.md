Role Name
=========

Does stuff!

This role is just an example of ansible

Requirements
------------

Ansible 2.2.0+ to run playbook

Role Variables
--------------

n/a

Dependencies
------------

ansbile git

Example Playbook
----------------

Run playbook to do stuff!

From inside provisioned VM or added to automation:

    ansible-pull -i 'localhost,' -c local -d /tmp/stuff -U https://github.com/scottlinux/ansible-demo

From one's workstation to provision a remote VM:

    git clone https://github.com/scottlinux/ansible-demo
    ansible-playbook -i "ip.address.of.target.server.vm," ansible-demo/local.yml

Run locally with ansible-playbook

    git clone https://github.com/scottlinux/ansible-demo
    ansible-playbook -i localhost, -c local ansible-demo/local.yml
     
License
-------

MIT

Author Information
------------------

@scottlinux
