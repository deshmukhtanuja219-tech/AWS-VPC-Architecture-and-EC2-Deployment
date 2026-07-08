# AWS VPC Architecture and EC2 Deployment 

#PROJECT OVERVIEW
In this project I created a custom VPC and public subnet. Attached an internet gateway to VPC to provide internet connectivity and Route the table with 0.0.0.0/0 with public subnet for any request outside the VPC can send to public subnet and associate subnet Route Table with public subnet after that lauched a EC2 instance and edit security table and allow http port 80 because with this anyone can access the application. Install apache webpage. Finally tested the application with public ip.

# SERVICES USED 
Amazon VPC
Public subnet
Internet gateway
Route table
Security group
EC2 instance

# IMPLEMENTATION STEPS
1. Created custom VPC
2. Created public subnet
3. Attached Internet Gateway
4. Configured Route Table
5. Associated Route Table with subnet
6. Created Security Group
7. Launched EC2 instances
8. Install web application
9. Tested my application

13. # OUTPUT
14. Successfully deployed application on EC2 within a custom vpc.

# SCREENSHOTS
## VPC
![vpc](https://github.com/deshmukhtanuja219-tech/AWS-VPC-Architecture-and-EC2-Deployment/blob/main/Screenshot%202026-06-28%20211138.png)

## Public Subnet
![Public Subnet](https://github.com/deshmukhtanuja219-tech/AWS-VPC-Architecture-and-EC2-Deployment/blob/main/Screenshot%202026-06-28%20211713.png)

## My Internet Gateway
![My Internet Gateway](https://github.com/deshmukhtanuja219-tech/AWS-VPC-Architecture-and-EC2-Deployment/blob/main/Screenshot%202026-06-28%20211951.png)

## My Route Table
![My Route Table](https://github.com/deshmukhtanuja219-tech/AWS-VPC-Architecture-and-EC2-Deployment/blob/main/Screenshot%202026-06-28%20212414.png)

## Server
![Server](https://github.com/deshmukhtanuja219-tech/AWS-VPC-Architecture-and-EC2-Deployment/blob/main/Screenshot%202026-06-28%20212949%20-%20Copy.png)
