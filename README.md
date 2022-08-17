[![singuyen027](https://circleci.com/gh/singuyen027/Capstone-Project-NguyenTS2.svg?style=svg)](https://circleci.com/gh/singuyen027/Capstone-Project-NguyenTS2)

#GET_PASSES_THIS_REPO_UDACITY_PLEASE


Cloud DevOps Engineer Nanodegree by Udacity: Capstone Project
What is this project is all about ?

The is the Capstone project of Udacity Cloud DevOps Nanodegree, where we need to showcase the skills which we obtained throughout this course.

In this project we used AWS for cloud
We used CircleCI to implement Continuous Integration and Continuous Deployment (CI/CD)
We used Ansible and CloudFormation to deploy clusters
We built Kubernetes clusters (AWS EKS)
We built Docker containers in pipelines (Dockerhub)
We have ensure to find linting errors and corrected the typographical errors.
Lastly, The CI/CD pipeline for microservices applications is developed with rolling deployment.

Getting Started
To get a local copy up and running follow these simple example steps.

Prerequisites
Create an AWS account
Connect Your Repository with CircleCI.
Create a Docker account.
EKS can be created manually by using the command below.
eksctl create cluster --name <cluster-name> --version 1.16 --nodegroup-name standard-workers --node-type t3.medium --nodes 3 --nodes-min 1 --nodes-max 4 --node-ami auto --region us-east-1
Setup the credentials in CircleCi for AWS credentials and dockerhub credentials
Installation
Clone the repo
git clone https://github.com/singuyen027/Capstone-Project-NguyenTS2
Run make lint to lint the app locally.
Run ./run-docker.sh and ./run-kubernetes.sh to run locally.
Upload the api to DockerHub by using ./upload-docker.sh
Used CircleCI for CI/CD
