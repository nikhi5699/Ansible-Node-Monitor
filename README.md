# Ansible-VM-Health-Reporter-
This project extracts VM metrices at a particular time on daily basis.

This project starts by creating 1 Master Node and 5 Control Nodes. Nodes here are AWS Ubuntu VM's

First passwordless authentication is setup using the .pem key onto Control Nodes to establish Master-Slave setup. 

Then the Dynamic Inventory is created using the Ip addresses of the Control Nodes. 
