# AWS-IAAC

Requirement:

3 tier environment in AWS(Cloud)

Tool used:AWS,Terraform

Here I have used Terraform to achieve the 3 tier environment

Terraform version:0.11

We are going deploy below mentioned resources using Terraform

RDS(replication) master and slave with read replica(Multi-AZ)
Auto-scaling groups and launch config
Load balancer for app and webserevr
2 ec2 for app and 2 for webserver
Security group for ecah resource
VPC(NAT,IG)

We are using accesskey and screatkey(AWS) as authentication from terrform server to provision AWS Resources.

As part of initailization ,We need to use terraform init command to downloads plugins and backends

We need to use terraform plan for dry run and terraform apply for provisioning infrastructure.

For Graphical represntation ,We need to use terraform graph
