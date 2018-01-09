# A complete and free High Availability RADIUS solution

## Components

- RADIUS server (Freeradius)
- Management GUI (TBA but seeing what comes with Freeradius first)
- Packerfile to bake an EC2 image
- Cloudformation or Terraform template to build an AWS environment

## AWS Environment

Solution will be located in AWS Sydney region (as Legion had been since 2014)
Solutuon should use 2 AWS Availability Zones for HA
- 1 x radiusd in each AZ
- AWS RDS (MySQL) with 1 x master in each AZ
- Console can optionally be HA also and may or may not use the same instance as RADIUS



