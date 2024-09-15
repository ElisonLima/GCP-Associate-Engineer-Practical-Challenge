# GCP-Associate-Engineer-Practical-Challenge
A hands-on repository with practical tasks to help prepare for the GCP Associate Cloud Engineer certification.

This repository contains a practical challenge for those preparing for the GCP Associate Cloud Engineer certification. The goal is to develop technical skills and apply the key concepts required in the certification, such as managing VMs, networking, storage, and security on Google Cloud Platform.


## Objectives

- Set up and manage resources on GCP using the Console and gcloud CLI.
- Manage and configure compute instances, networking, and storage.
- Work with Kubernetes Engine, App Engine, and Cloud Functions.
- Implement performance monitoring and optimization solutions.
- Manage permissions and access with IAM (Identity and Access Management).

## Challenge

### Project Setup and Initial Configuration

- Create a new project on GCP and set it up with a budget policy and cost alerts.
- Document the environment setup process in the README.md.

### Compute Engine: Managing VM Instances

- Create a custom VM instance using the gcloud CLI.
- Configure a startup script to install a web server (Apache or Nginx).
- Create snapshots of the VM for backup purposes.
Set appropriate access permissions (IAM) for the VM.

### Networking: Configuring VPCs

- Create a VPC with custom subnets.
- Set up firewall rules to allow only HTTP and SSH access.
- Create a VPN between two VPCs in different regions.

### Cloud Storage: Managing Buckets and Objects

- Create a bucket in Cloud Storage and define storage classes (Standard, Nearline).
- Upload files to the bucket and configure public access policies.
- Implement a lifecycle policy to move data to Coldline after 30 days.

### Kubernetes Engine (GKE): Application Deployment

- Create a GKE cluster and deploy a simple application (e.g., a container with a web app).
- Expose the service via a Load Balancer.
- Set up autoscaling for the cluster.


### Cloud Functions and App Engine

- Create a Cloud Function that responds to an HTTP request with a personalized message.
- Deploy an application to App Engine with a simple REST API.


### IAM: Access Management

- Set up specific IAM roles for different users in the project.
- Create a service account with minimal permissions for performing a specific task.


### Monitoring and Logging with Stackdriver

- Implement monitoring for the VM and the App Engine application using Stackdriver.
- Set up monitoring alerts triggered by CPU usage or HTTP errors.


### Optimization and Cost Solutions

- Analyze resource usage and suggest optimizations (e.g., instance sizes, storage classes).
- Document improvements made to optimize costs.

### Rules:

- All created resources must be documented, explaining the purpose and creation process.
- Use screenshots or the gcloud CLI command history in the README.md to show progress.
- The code for the function or web application must be available in the repository.
