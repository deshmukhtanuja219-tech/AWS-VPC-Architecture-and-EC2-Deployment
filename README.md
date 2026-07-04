# AWS VPC Architecture and EC2 Deployment AND APPLICATION LOAD BALANCER

#PROJECT OVERVIEW
In this project I created a custom VPC and public subnet. Attached an internet gateway to VPC for internet connectivity and Route the table with 0.0.0.0/0 with public subnet for any request outside the VPC can send to public subnet and associate subnet Route Table with public subnet after that lauched a EC2 instance and edit security table and allow http port 80 because with this anyone can access the application. Creted target group and register EC2 instance in Target Group. Attach target group to load balance . Target group receives traffic from application load balance and check healthy instances and send it to healthy instance, if their any unhealthy instance detects then stop routing traffic.Finally tested the application.

# SERVICES USED 
Amazon VPC
Public subnet
Internet gateway
Route table
Security group
EC2 instance
Load Balancer

# IMPLEMENTATION STEPS
1. Created custom VPC
2. Created public subnet
3. Attached Internet Gateway
4. Configured Route Table
5. Associated Route Table with subnet
6. Created Security Group
7. Launched EC2 instances
8. Install web application
9. Created Target Group
10. Created application Load balance
11. Registered EC2 instance in Target Group
12. Tested Application using Load Balancer DNS

13. # OUTPUT
14. Successfully deployed application on EC2 within a custome VPC and Load Balancer distribute traffic in healthy instances and perform health check.

AWS VPC Architecture and EC2 Deployment AND APPLICATION LOAD BALANCER
#PROJECT OVERVIEW In this project I created a custom VPC and public subnet. Attached an internet gateway to VPC for internet connectivity and Route the table with 0.0.0.0/0 with public subnet for any request outside the VPC can send to public subnet and associate subnet Route Table with public subnet after that lauched a EC2 instance and edit security table and allow http port 80 because with this anyone can access the application. Creted target group and register EC2 instance in Target Group. Attach target group to load balance . Target group receives traffic from application load balance and check healthy instances and send it to healthy instance, if their any unhealthy instance detects then stop routing traffic.Finally tested the application.

SERVICES USED
Amazon VPC Public subnet Internet gateway Route table Security group EC2 instance Load Balancer
IMPLEMENTATION STEPS
Created custom VPC
Created public subnet
Attached Internet Gateway
Configured Route Table
Associated Route Table with subnet
Created Security Group
Launched EC2 instances
Install web application
Created Target Group
Created application Load balance
Registered EC2 instance in Target Group
Tested Application using Load Balancer DNS

OUTPUT
Successfully deployed application on EC2 within a custome VPC and Load Balancer distribute traffic in healthy instances and perform health check.

# SCREENSHOTS
## VPC
![vpc](https://github.com/deshmukhtanuja219-tech/AWS-VPC-Architecture-and-EC2-Deployment/blob/main/Screenshot%202026-06-28%20211138.png)

## Internet Gateway


