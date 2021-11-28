# A simple VPC set up with one EC2 instance and its security group all in a

## This contains the following core AWS resources:

1. VPC

2. Security group

3. EC2 instance

## The following Terraform blocks are created:

1. Variables: (Access Key, Secrety Key, Private Key Path, Key Name and Region)

2. Provider: AWS

3. Data Block: AMIS available

4. AWS resource block 1: VPC

5. AWS resource block 2: Security Group

6. AWS resource block 3: AWS Instance

7. Provisioner: Type "remote exec"

8. Output block
