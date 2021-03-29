# Arth_Task19_Created_K8S_Cluster_Role_Using_Ansible
## Created Ansible Roles to Configure Kubernetes Cluster. It is completely automated

# Steps

### 1. First launched EC2 instances using aws_ec2_instances.yml. In this i have used vault to secure my AWS credentials
### 2. Then created two roles, one for master and one for slaves
### 3. And then created one setup.yml playbook to setup complete cluster
### 4. Only thing you will have to do that copying token and pasting in var foleder of tokens variable in K8SWorkers role

![alt text](https://miro.medium.com/proxy/1*J6_1Q2IuToIbEu0Oz2TO2w.jpeg)
