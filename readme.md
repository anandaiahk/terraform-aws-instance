# terraform aws instance

this is create ec2 instance in aws.

## inputs
+ project - (required) string type, user must provide project name.ex roboshop, expense etc.
+ environment - (required) string type, user must provide environment name. ex dev,prod etc.
+ ami_id - (required) string type, user must provide ami_id of the instance.
+ instance_type - (optional) string type, default value is t3.micro users can override.
+ sg_ids - (required) list of sting, user must provide list of securiy group ids. instance should have.
+ tags - (optional) map type ,user can provide the tags they want to have.

## outputs
+ instance_id - ID of the instance created
+ public_ip - public ip of the instance
+ private_ip - private ip of the instance
