# Terraform AWS VPC

This module creates following resources

1. VPC
2. IGW with VPC association
3. Subnets -› public, private, database
4. Route tables -> Public, private, database
5. Associtaions and Routes
6. EIP
7. NAT gateway
8. VPC Peering with default VPC on condition
9. Rout table entries through peering

## Inputs
project - (Required) string type. User should pass the project name
environment - (Required) string type. User should pass the environment, values should be one of dev, uat, qa and prod

## Outputs