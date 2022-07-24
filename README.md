# K8s-Jenkins-Pipeline-Setup-on-AWS

Guide for settting up Jenkins pipeline and deploy to kubernetes cluster hosted on AWS

## Steps

1. Setup an AWS EC2 Instance for hosting Jenkins Server
2. Connect to EC2 and Install JDK, Jenkins
3. Install Docker
4. Setup Docker Hub Account
5. Install AWS CLI, Kubectl, eksctl
6. Here we clone the application from GitHub, we build the docker image from docker file then we push that docker image build to docker hub repository.(This process is automated, defined in Jenkins pipeline)
7. Create EKS cluster using command.
8. Add pipeline stages to jenkins
9. Build, Deploy and test CI/CD pipeline
