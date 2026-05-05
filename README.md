\# Terraform EC2 Project



\## Objective



To create an EC2 instance in AWS using Terraform.



\## Tools Used



Terraform, AWS CLI, AWS EC2, GitHub



\## Configuration



Region: ap-south-1

Instance Type: t3.micro

AMI: Amazon Linux

Tag Name: Terraform-Student-Instance



\## Steps



1\. Install Terraform and AWS CLI



2\. Configure AWS using:

&#x20;  aws configure



3\. Initialize Terraform:

&#x20;  terraform init



4\. Check the plan:

&#x20;  terraform plan



5\. Create instance:

&#x20;  terraform apply



6\. Delete instance:

&#x20;  terraform destroy



\## Output



The public IP of the EC2 instance is displayed after creation.



\## Notes



\* Only one instance is created

\* Instance is deleted after testing to avoid charges
“Faced issue with t2.micro, resolved using t3.micro”
“Verified instance creation and deletion successfully”


\## Result



EC2 instance was successfully created and deleted using Terraform.



