## Project Overview

This project develops on the previous AWS Virtual Private Cloud (VPC) using AWS CloudFormation and YAML.

The objective is to create a launch template that will autoscale traffic over 2 subnets, including a scale out policy and CloudWatch alarm, to be built out in stages, documenting each stage and maintaining a clear Git history.

## Technologies

- Amazon Web Services (AWS)
- AWS CloudFormation
- YAML
- Git and GitHub
- Windows PowerShell

## Development Roadmap
Prepare - Use the existing VPC foundation: Copy over the original code for VPC, subnet, IGW, route tables and associations. Add the previously coded Security Group: allowing tcp traffic inbound from anywhere.
Stage 1 - Launch Template: Add the launch template defining instance type, security group & bash script.
Stage 2 - Auto Scaling Group: Add the auto scaling group with min, max and desired capacity to be linked to public subnets.
Stage 3 - CloudWatch Alarm: Add cloudwatch alarm when CPU utilisation exceeds 70%.
Stage 4 - Scale Out Policy: Add scale out policy to define action of the cloudwatch alarm.
Stage 5 - Validation and documentation: Validate the template, review security and document limitations and future improvements.

## Repository Structure

- templates/asg.yaml - CloudFormation Auto Scaling Group template.
- docs/development-log.md - Development and implementation notes.

## Status

Completed. The repository has been created in stages, with each stage recorded in Git commits.

## Security and Cost Notice

Review security group rules, AMI compatibility and AWS Region settings before deployment. Creating AWS resources may incur charges.

**Write-up:** (https://medium.com/@rwstokes3/scaling-out-with-auto-scaling-groups-using-cloudformation-bbb47a4bb4b6)
