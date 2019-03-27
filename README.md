# MyAnsibleRepo

========================================

Ansible session #1 assignment

========================================


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

==========================================================

Session #2 homework

==========================================================

1. Your current playbooks have tasks, vars, handlers - turn them into roles:

    The first role will replace the configure_base_server.yml playbook and setup your basic server - name it common

    The second role will replace the playbook from our last session (db_setup.yml) and will setup your database  - name it db

    The third role will replace task in webserver_setup.yml - name it webserver

    At this point your roles needs to use defined vars and not hardcoded params (ntp servers, package location etc.)

2.  Add to your  inventory file the db node as well

3.  Create a playbook to install and configure our db server with the following roles:

    Common  db

   4. Create a playbook to install and configure our webserver with the following roles:


    Common  webserver


Make sure to run your playbooks before submitting
