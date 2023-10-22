Project: Coworking Space Service
The Coworking Space Service is a set of APIs that enables users to request one-time tokens and administrators to authorize access to a coworking space.

This service follows a microservice pattern and the APIs are split into distinct services that can be deployed and managed independently of one another.

For this project, you are a DevOps engineer who will be collaborating with a team that is building an API for business analysts. 
The API provides business analysts with basic analytics data on user activity in the coworking space service. The application they provide you functions 
as expected, and you will help build a pipeline to deploy it to Kubernetes.

---------------------------------------
Workspace Environment Requirements
If you're using your own local computer, you'll need:

- Python Environment - run Python 3.6+ applications and install Python dependencies via pip
- Docker CLI - build and run Docker images locally
- kubectl - run commands against a Kubernetes cluster
- helm - apply Helm Charts to a Kubernetes cluster
- GitHub - pull and clone code

Remote Resource Requirements

- AWS CLI
- AWS CodeBuild - build Docker images remotely
- AWS ECR - host Docker images
- Kubernetes Environment with AWS EKS - run applications in k8s
- AWS CloudWatch - monitor activity and logs in EKS

---------------------------------------
Configure and deploy the Project
- Create AWS resource
- Config Kubect with EKS Cluster Name
- Set up PostgreSQL with Helm Chart
- Seed data using kubectl port-forward and psql
- Create AWS CodePipeline to build and push image to AWS ECR
- Create a service and deployment yaml files to deploy web api
- Apply configmap, secret, service and deployment yaml files
- Create an external load balancer using kubectl expose
- Check web api
- Check logs from CloudWatch

---------------------------------------
Link web:  