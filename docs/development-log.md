# Development Log

## Stage 1 - VPC Foundation & Creation of Auto Scaling Group

### Implemented
- Created the initial VPC CloudFormation template using previous VPC code.
- Used the initial security group from previous 
- Create the Launch Template & configured with a bash script for start up.

### Outstanding
- Auto Scaling Group: Add the auto scaling group with min, max and desired capacity to be linked to public subnets.
- Create CloudWatch Alarm: Add cloudwatch alarm when CPU utilisation exceeds 70%.
- Create Scale Out Policy: Add scale out policy to define action of the cloudwatch alarm.
- Validation and documentation: Validate the template, review security and document limitations and future improvements.

### Validation
- Pending CloudFormation template validation.
- Deployment not yet performed.

## Stage 2 - VPC Foundation & Creation of Auto Scaling Group

### Implemented
- Created the Auto Scaling Group. Configured with min, max and desired capacity to be linked to public subnets.

### Outstanding
- Create CloudWatch Alarm: Add cloudwatch alarm when CPU utilisation exceeds 70%.
- Create Scale Out Policy: Add scale out policy to define action of the cloudwatch alarm.
- Validation and documentation: Validate the template, review security and document limitations and future improvements.

### Validation
- Pending CloudFormation template validation.
- Deployment not yet performed.