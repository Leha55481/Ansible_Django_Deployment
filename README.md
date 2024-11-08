# Ansible_Django_Deployment
Bunch of ansible books for deploying django CMS, and some monitoring on a separate server

INSTALL INSTRUCTIONS

Clone all files into your linux machine

Open Common_Variables.yml and change all credentials, ips, and domain

Run Ansible_Django.yml, Ansible_Node_Exporter.yml, Ansible_Promtail.yml on your web server
Run Ansible_Grafana.yml on your monitoring server

Grafana can be accessed at monitoring_ip:3000
