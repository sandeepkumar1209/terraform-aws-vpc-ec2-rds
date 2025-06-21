1.Create a VPC
2.Create an Internet Gateway and attach it to the VPC
3.Create 3 subnets: 1 public for EC2 and 2 private for RDS
4.Create 2 route tables: 1 public and 1 private
5.Create 2 security groups: 1 for EC2 and 1 for RDS
6.Create the DB subnet group
7.Create the MySQL RDS database
8.Create the EC2 instance
9.Verify that everything is set up correctly

Ref: https://medium.com/strategio/using-terraform-to-create-aws-vpc-ec2-and-rds-instances-c7f3aa416133

