# Ansible-VM-Health-Reporter-
This project extracts VM metrices at a particular time on daily basis.

This project starts by creating 1 Master Node and 5 Control Nodes. Nodes here are AWS Ubuntu VM's

First passwordless authentication is setup using the .pem key onto Control Nodes to establish Master-Slave setup. 

Then the Dynamic Inventory is created using the Ip addresses of the Control Nodes. 

![WhatsApp Image 2025-07-29 at 22 44 55_3ac00f55](https://github.com/user-attachments/assets/92a10bfb-2f72-4f9b-a7a7-915cfe1a3b42)
