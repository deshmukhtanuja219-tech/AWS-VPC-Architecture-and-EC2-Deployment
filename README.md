# AWS VPC Architecture and EC2 Deployment

#PROJECT OVERVIEW
In this project I created a custom VPC and public subnet. Attached an internet gateway to VPC for internet connectivity and Route the table with 0.0.0.0/0 with public subnet for any request outside the VPC can send to public subnet and associate subnet Route Table with public subnet after that lauched a EC2 instance and edit security table and allow http port 80 because with this anyone can access the application. Creted target group and register EC2 instance in Target Group and attach target group to load balance . Target group receives traffic from load balance and check healthy instances and send it to healthy instance, if their any unhealthy instance detects then stop routing traffic.Finally tested the application.

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
14. Successfully deployed application on EC2 within a custome VPC and Load Balancer distribute traffic in healthy instances.
