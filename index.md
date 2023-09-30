# My Projects on GitHub
---
## AWS Useful Scripts

### AWS Assume Role Scripts
Useful scripts for getting assume role/ temp credentials for aws accounts.

The repository contains two script files. Any of these scripts can be used to get the credentials from the AWS account based on the feasibility.
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/mahesh031/aws-assume-role-scripts)

<center><img src="assets/img/aws-iam.png"/></center>


---
### AWS Jump Host Scripts

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/mahesh031/aws-jump-host-scripts)

Scripts provide easy way getting access to provate EC2 instances behind Jump host server

Most of the deployments on AWS includes public and private subnets.
On public subnets, jump host server will be running in the form of EC2 instance and are publicly accessible using pre-built trust mechanisms such as by using SSH key pairs.
On private subnets, all the services will be running inside the docker containers on EC2 instance.

While troubleshooting the issue, most of the times, one has to get into this machines and run few commands to check if the containers are up or check the docker logs. Since this is mundane task, having the script which does this in an automated way would be desirable.

<center><img src="assets/img/aws-iam.png"/></center>


