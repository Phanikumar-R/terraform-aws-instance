# Terraform aws instance flow for later rivision

This module created EC2 instance in AWS .

## Inputs
- Project -(Required) (string)- User must provide project name ex: Roboshop,expense
- Environment -(Required)-(String)-User must provide env name ex;Dev,Prod
- ami_id-(Required)- (String)- User must provide ami_id of the instance
- instance_type (Optional)-string type.Default value is t3.micro.User can override
- sg_id's-(Required) -List (string)-User must provide list of SG_id's
- tags( OPtional) -Need to be placed at last


## outputs

- instance_id () -ID of the instance created
- public_ip - public ip of the instance generated
- private_ip -private ip of the instance generated 

