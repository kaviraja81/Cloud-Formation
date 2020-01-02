# Cloud-Formation
Cloud Formation Templates to create VPC using YAML
 This file is used to create a VPC and 2 subnets -one public and one private subnets. I have used the !Ref feature and created the cloud formation template in YAML 
!GETAZ- is used to get the list of availability zones in the region.
!SELECT feature is to select a particular value from the array. 0 is the first number of the array sequence.   
1 .Create a VPC 
2.Create a public subnet
3.Create a private subnet
4. Create an Internet Gateway
5. Attach the internet gateway to the VPC
