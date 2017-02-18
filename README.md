ansible-openssh-server
======================

This role manage openssh-server

[![Ansible Galaxy](https://img.shields.io/ansible/role/xxxx.svg)](https://galaxy.ansible.com/salamachinas/openssh-server/)

Requirements
------------

This role requires Ansible 2.0 or higher and platform requirements are listed
in the metadata file.

Install
-------

```sh
ansible-galaxy install salamachinas.openssh-server
```

Tests
-----

```sh
docker build -t test-ansible-openssh-server-centos7 -f tests/Dockerfile_centos7 --force-rm .
docker build -t test-ansible-openssh-server-debian7 -f tests/Dockerfile_debian7 --force-rm .
docker build -t test-ansible-openssh-server-debian8 -f tests/Dockerfile_debian8 --force-rm .
docker build -t test-ansible-openssh-server-ubuntu14 -f tests/Dockerfile_ubuntu14 --force-rm .
docker build -t test-ansible-openssh-server-ubuntu16 -f tests/Dockerfile_ubuntu16 --force-rm .
```
