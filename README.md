# Ansible Role: Adminer

[![Build Status](https://travis-ci.org/geerlingguy/ansible-role-adminer.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-adminer)

An Ansible Role that installs [Adminer](http://www.adminer.org/) on almost any computer.

## Requirements

You need to have PHP and MySQL for Adminer to do anything useful.

## Role Variables

TODO

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - { role: geerlingguy.adminer }

## License

MIT / BSD

## Author Information

This role was created in 2015 by [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/). It is originally a fork of [Oefenweb/ansible-adminer](https://github.com/Oefenweb/ansible-adminer).
