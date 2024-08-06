# Kubernetes Cluster Setup on Centos9 stream Using Ansible Playbooks
Provides Ansible playbook to setup a K8s Cluster (1 Manager and N workers)

# General
This code was written so we can test kubernetes clusters on local machines. But the main purpose of this code is to create kubernetes clusters on bare metal machines. 

# Requirements
What you need to have installed on ansible host:

ansible
kubectl

This playbook only works on CentOS/RedHat

# check the ansible playbook syntax
ansible-playbook --syntax-check playbook.yml -i hosts

# run the playbook
ansible-playbook playbook.yml -i hosts
