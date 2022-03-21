# LEUMI

PHASE#1
========
The task was created as following:

1. EC2 instance (Ubuntu Server 20.04) was created in AWS
2. Jenkins installed on the EC2 instance
3. custom port 8080 opened in security group
4. minikube installed on EC2
5. jenkins configured with minikube credential
6. pipeline created to run a job. The job creates a pod (bank-leumi-XXX). the pod log gives the output "Hello Bank Leumi" 

* attached files:
 > Jenkins_pipeline.rtf
 > job.yaml
 > EC2_Minikube_jenkins_yaml_pipeline.mp4


PHASE#2
=========

1. Docker file created : Dockerfile.rtf (need to be rename to Dockerfile if need to create image)
2. shell script created : leumi_script.rtf file (need to be rename to leumi_script.sh)
3. docker image created and uploaded to the : https://hub.docker.com/  (https://hub.docker.com/repository/docker/talash/leumi)
4. pod.yaml created (pod.yaml.txt)

* attached files:
> Dockerfile.rtf
> leumi_script.rtf
> pod.yaml.txt

