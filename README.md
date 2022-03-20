# LEUMI

The task was created as following:
1. EC2 instance was created in AWS
2. Jenkins installed on the EC2 instance
3. custom port 8080 opened in security group
4. minikube installed on EC2
5. jenkins configured with minikube credential
6. pipeline created to run a job. The job creates a pod (bank-leumi-XXX). the pod log gives the output "Hello Bank Leumi" 
