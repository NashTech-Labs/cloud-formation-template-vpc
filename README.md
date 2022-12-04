# AWS CLOUDFORMATION:
AWS CloudFormation enables you to create and provision AWS infrastructure deployments predictably and repeatedly. It helps you leverage AWS products such as Amazon EC2, Amazon Elastic Block Store, Amazon SNS, Elastic Load Balancing, and Auto Scaling to build highly reliable, highly scalable, cost-effective applications in the cloud without worrying about creating and configuring the underlying AWS infrastructure. AWS CloudFormation enables you to use a template file to create and delete a collection of resources together as a single unit (a stack).

# Pre-Rerequisites:
- AWS Account
- AWS account configure if you want to build with aws cli

# How to build resources with template:
**We can build stack in two ways**  
1 AWS CLI  
2 AWS MANAGEMENT CONSOLE
- aws cli  
  `aws cloudformation create-stack --stack-name cfn-demo --template-body file://   vpc_template.yaml`
- aws management console  
  `click on create stack upload yaml file it will create resource define in template yaml file`
- Describe created stack  
  `aws cloudformation describe-stacks --stack-name cfn-demo`
