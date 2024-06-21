## AWS-Infrastructures-and-Servers-for-Web-Application-Deployment
This project creates Cloud Infrastructures and Servers for Web Application Deployment with AWS CloudFormation

The network template deploys a VPC, with a pair of public and private subnets spread 
across two Availability Zones and putting security measures in place

It deploys an Internet Gateway, with a default 
route on the public subnets. 

It deploys a pair of NAT Gateways (one in each AZ), 
and default routes for them in the private subnets.
