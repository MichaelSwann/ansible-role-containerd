Containerd
=========

A role for installing and configuring containerd

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

It is a good idea include a tool which can inspect and monitor the containers
crictl_version: 'v1.19.0'


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - containerd

License
-------

BSD

Author Information
------------------

Michael Swann <michael@telviva.com>
