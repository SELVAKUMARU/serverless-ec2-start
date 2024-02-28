# serverless-ec2-start

We have a script to start ec2 instances using python script based on tags.

Prerequisites

* An AWS Account with An IAM User with IAM, Lambda, EC2 Access

* Serverless framework installed

Launch EC2 instances

Launch instances and add tags, if instances already exists just add start: ec2 tags to instances. 

Note: You may give your own tags


Here we have achieved this by Serverless Framework

Steps to Proceed

1. Clone the code in your local machine

2. Change the code as per your requirement

3. Deploy your code by below command and ensure that you have installed serverless framework in your local machine.

   sls deploy  --region <region> --aws-profile <profile-name> --stage dev

Resource clean up that you did through Serverless 

   sls remove  --region <region> --aws-profile <profile-name> --stage dev


Happy Coding!!!!


