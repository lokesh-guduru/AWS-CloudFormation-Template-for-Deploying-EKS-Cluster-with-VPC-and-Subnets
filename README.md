# AWS-CloudFormation-Template-for-Deploying-EKS-Cluster-with-VPC-and-Subnets

This is an AWS CloudFormation template written in YAML format, which describes an infrastructure stack to create an Elastic Kubernetes Service (EKS) cluster using an Amazon Virtual Private Cloud (VPC) with two public and two private subnets.

It includes definitions of resources such as the VPC, subnets, internet gateway, route tables, and NAT gateways. These resources are created and configured using the parameters defined in the YAML file.

The YAML file also uses mapping to define IP ranges, availability zones, and subnet CIDR blocks.

The purpose of this file is to provide a way to automate the creation of an EKS cluster in AWS. By using AWS CloudFormation, users can define their infrastructure as code and quickly create and modify their resources with version control and repeatable processes.
