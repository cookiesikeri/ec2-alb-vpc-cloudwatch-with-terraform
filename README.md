how to run infra 

* `terraform init` is to initialize the working directory and downloading plugins of the AWS provider
* `terraform plan` is to create the execution plan for our code
* `terraform apply` is to create the actual infrastructure. It will ask you to provide the Access Key and Secret Key in order to create the infrastructure. So,     instead of hardcoding the Access Key and Secret Key, it is better to apply at the run time.


After terraform apply completes you can verify the resources on the AWS console. Terraform will create the below resources.
* VPC
* Auto Scaling Group
* Launch Configurationn
* Auto Scaling Policy
* Load Balancer
* Internet Gateway
* Route Table
* Security Groups
* Subnets
* Cloud Watch Alarm

