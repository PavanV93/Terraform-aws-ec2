# Terraform AWS EC2 Module

# Inputs:

* ami_id (Optional): ami_id is optional. Default value is ami-041e2ea9402c46c32
* security_group_ids (Optional): list of security group ids. default is sg-0adbc3f247a4e7736
* instance_type(Optional): Default value is t3.micro.
* tags(Optional): Default value is empty.

# Outputs:

* public_ip: outputs the public IP of the instance created.
* private_ip: outputs the private IP of the instance created.
* instance_id: outputs the instance ID created.