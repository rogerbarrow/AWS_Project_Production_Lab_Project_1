# AWS_Project_Production_Lab_Project_1
This example demonstrates how to create a vpc that you for servers in a production environment to improve resiliency
Project-#1 & To improve resiliency, you deploy the servers in two availability zone, by using an Auto Scaling group and an Application Load Balancer , for additional security,you deploy the servers in private subnets, The servers receive requests through the load balancer. The servers can connect to the internet by using a NAT gateway. To improve resiliency, you deploy the NAT gateway in both Availability Zones

AWS Public and Private Subnet Architecture 
![image](https://github.com/rogerbarrow/AWS_Project_Production_Lab_Project_1/assets/46138186/2d65618d-56a7-44b5-9984-62c56ccaa968)



Services involved: AWS

Prerequisites

Load balancer
NAT Gateway
Auto Scaling Group
Bastion Host or Jump server 


Step 1: Create VPC with 2 Availiablity zone, 2 private subnets, 2 public subnets and 1 Nat gateway  s3 gateway isnt required for this project you can remove it as a endpoint 

![image](https://github.com/rogerbarrow/AWS_Project_Production_Lab_Project_1/assets/46138186/05815805-b5cd-49b5-b25f-410d2cc3ad3b)

![image](https://github.com/rogerbarrow/AWS_Project_Production_Lab_Project_1/assets/46138186/01619c82-cc61-4377-8582-64903fb48a76)

Step 2: create your virtual Machine mkdir /f/vargrant-vm/finance vagrannt init eurolinux-vagrant/centos-stream-9 vagrant up vagrant ssh
