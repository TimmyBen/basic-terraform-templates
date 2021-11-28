# A simple VPC containing one EC2 instance and its security group.

## This contains the following core AWS resources:

1. VPC

2. Internet Gateway

3. Subnet 1

4. Subnet 2

5. Route Table with route out to the internet

6. Route Table Association for Subnet 1

7. Route Table Association for Subnet 2

8. A Security Group for the Load Balancer that allows in port 80 traffic from an source

9. A Security Group for the EC2 instances that only allows in traffic from IP addresses within the VPC's address space

10. Load Balancer resource connected to two EC2s

11. EC2 Instance 1

12. EC2 Instance 2

13. Output block for Load Balancer DNS name
