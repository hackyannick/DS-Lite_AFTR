# DS-Lite-builder



![Fig 6](https://github.com/hackyannick/DS-Lite_AFTR/blob/main/files/pict.png?raw=true)



Buildung a AFTR for my DSL Homelab

Ansible software was used in order to automate the porcess of building the machines (AFTR).


Just get the toplogy built, as shown in the the above topoloy.

All machines are CentOS-7 and built using VMware Workstation Player.

Pre-requisites:-

1- yum update

2- yum install epel-release

3- yum install ansible

To runn the installation scripts, run the below commannds: -
On AFTR Router: -

ansible-playbook AFTR.yml
