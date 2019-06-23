Jenkins Slave Configuration
============================
Configure Linux machines to be used as a Jenkins Slave.

Requirements
------------
Centos Machines (Machines to be configured as slaves)
public key to be present (id_rsa.pub) at user .ssh directory

Role Variables
--------------
ansible_user : < Remote machine username >

Example Playbook
----------------
Example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: LIN-DPL
  
  roles:
  - role: LIN-DPL
