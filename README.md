**CICD Pipeline Using > Git > Jenkins > Ansible > DockerHub > Kubernetes**

**STEPS:**

1)Deploying AWS Instances with Terraform:
Install Terraform on your local machine.
Configure your AWS secret key.
Execute 'terraform init' and 'terraform plan'.
If successful, apply changes with 'terraform apply'.
Installing Ansible:

2)After instances are deployed, install Ansible on one instance using provided files.

3)Installing Jenkins:Install Jenkins on an instance and configure it using the setup file.

4)Installing Docker:
Install Docker on the instance and authenticate with Docker Hub using 'docker login'.

5)Deploying EKS Cluster with CloudFormation:
Deploy an EKS cluster on AWS using CloudFormation.
Use Ansible ('kube_deploy') to configure Load Balancer post-deployment.

6)Running Jenkins CI/CD Build:
Complete the setup by initiating a Jenkins CI/CD build.



<img width="1378" alt="DevOps_Project _Flow" src="https://github.com/pallavithorat/DevOps-Project/assets/87472620/12743ea6-1a9a-4960-85c3-6b7e44a243d1">
