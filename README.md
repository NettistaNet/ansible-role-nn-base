Role Name
=========

Base role for NettistaNet clusters. Currently just installs some required packages.

Requirements
------------

This role was created to be used with some other roles to prepare some nodes to be ready for Kubernetes setup using Kubespray).

Currently only debian-based distributions are supported.


Role Variables
--------------

None

Example Playbook
----------------

This role can be easily used in a playbook like this:

- hosts: all
  roles:
      - ansible-role-nn-base

License
-------

GNU GENERAL PUBLIC LICENSE VERSION 3

Author Information
------------------

[blog.retter.jetzt](https://blog.retter.jetzt)