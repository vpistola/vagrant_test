vagrant-test
============

## Description

This sets up a test Ubuntu cluster with 1 Master and 2 Slaves with default settings.

Vagrant & Ansible are used to provision 3 Ubuntu 18.04 LTS (hashicorp/bionic64) VMs with a private network and the following roles:

192.168.33.10	master	
192.168.33.11	slave-s1	Slave 1
192.168.33.12	slave-s2	Slave 2

## Requirements

- Install Vagrant: https://www.vagrantup.com/downloads
- Install Ansible: https://docs.ansible.com/ansible/latest/installation_guide/index.html

## Instructions

- git clone
- vagrant up
