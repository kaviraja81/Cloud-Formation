# Cloud-Formation
Cloud Formation Templates to create VPC using YAML

 This file is used to create a VPC and 2 subnets -one public and one private subnets. I have used the !Ref feature and created the cloud formation template in YAML 
!GETAZ- is used to get the list of availability zones in the region.
!SELECT feature is to select a particular value from the array. 0 is the first number of the array sequence.   
 
 1 .Create a VPC 

 2.Create a public subnet
 
 3.Create a private subnet
 
 4.Create an Internet Gateway
 
 5.Attach the internet gateway to the VPC
 
 6.Create an Elastic IP address 
 
 7.Create a NAT Gateway with the created EIP
 
 8.Create Public Route Table.Attach Internet Gateway to the Public Route Table
 
 9.Create Private Route Table Attach NAT gateway to the private route table
 
 10.Associate Public subnets to the Public Route table
 
 11.Associate Private subnets to the Private Route table

With this YAML, an entire new VPC can be created with 2 public subnets,2 private subnets and their corresponding route tables can be created. The Internet Gateway adn the NAT gateway are also created and attached to the route tables 

