# MyAnsibleRepo
Contains all relevant files for the home assignments related to Ansible

========================================

Ansible session #1 assignment

========================================
Session #1 assignment



Complete the rest of the videos 


For the next tasks reference the repo below


Create a new playbook with a single play. Playbook should:

Add EPEL repo 

Make ntp package installed

Add ntp.conf

Restart ntp service 

Name it configure_base_server.yml and run playbook on both nodes created. 


Create another playbook webserver_setup.yml  for installing a webserver Install httpd package

Add index.html to /var/www/html 

On your ansible server node create a new host (/etc/hosts) record with node1.opsschool.com pointing to node1 ip address

Verify that server responds to http request and returns status 200

Run this playbook on webserver group


Upload your playbooks to a private repo (could be a tgz file) and submit it as your answers


* Use the following for static files:

https://raw.githubusercontent.com/shayharush/opsschol-ansible/master/session1/files/index.html
https://raw.githubusercontent.com/shayharush/opsschol-ansible/master/session1/files/ntp.conf
Remeber to create an inventory file with your groups included

