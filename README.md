# AWS_Project_Production_Lab_Project_1
This example demonstrates how to create a vpc that you for servers in a production environment to improve resiliency
Project-#1 & To improve resiliency, you deploy the servers in two availability zone, by using an Auto Scaling group and an Application Load Balancer , for additional security,you deploy the servers in private subnets, The servers receive requests through the load balancer. The servers can connect to the internet by using a NAT gateway. To improve resiliency, you deploy the NAT gateway in both Availability Zones

Services involved: AWS

Prerequisites

Load balancer
NAT Gateway
Auto Scaling 
Git bash or equivalent editor
Step 1: Get you Website Get a Worpress template from tooplate.com

Step 2: create your virtual Machine mkdir /f/vargrant-vm/finance vagrannt init eurolinux-vagrant/centos-stream-9 vagrant up vagrant ssh
