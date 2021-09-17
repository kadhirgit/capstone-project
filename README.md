

# capstone-project

Its a Udacity DevOps Capstone project to deploy an app in AWS EKS 

Below are the steps performed 

1. Build a html application

2. Containerize the application using Docker and push it to DockerHub

3. Pull the application from DockerHub into AWS-ECR

4. Create a EKS cluster and required nodes

5. Setup Load Balancer

6. Delete all post completion


The following environment variablesz must be set for the project on CircleCI via the project settings page, before the project can be built successfully.

Variable	Description
AWS_ACCESS_KEY_ID	          Used by the AWS CLI
AWS_SECRET_ACCESS_KEY	      Used by the AWS CLI
AWS_DEFAULT_REGION	        Used by the AWS CLI. Project value: "ap-south-1"
AWS_ECR_URL	                Identifies the AWS ECR docker image registry that the docker image will be pushed to, in the format                   AWS_ACCOUNT_ID.dkr.ecr.AWS_DEFAULT_REGION.amazonaws.com
