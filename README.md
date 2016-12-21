[![Build Status](https://travis-ci.org/maxim-nazarenko/ansible-role-example.svg?branch=master)](https://travis-ci.org/maxim-nazarenko/ansible-role-example)


Ansible example role for OpenLDAP server
========================================

Install and configure an OpenLDAP server from scratch

Requirements
------------

This role is a standalone role.

Role Variables
--------------

ldap_domain:
  LDAP doamin to be used as primaty domain
  Example: domain.local


  ldap_organization:
    The organization name
    Example: "My org, Inc."

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: ldap-servers
      roles:
         - role: ansible-role-example
           ldap_domain: 'example.com'
           ldap_organization: 'Example org, LLC.'

License
-------

MIT

Author Information
------------------

Maxim Nazarenko <maxim.nazarenko@onix-systems.com>
