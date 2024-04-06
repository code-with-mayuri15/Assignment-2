DevOps Assignment 2: Kubernetes - Dynamic Scaling with HPA and Load Testing
This project demonstrates a real-world DevOps scenario where a Node.js application is deployed on a Kubernetes cluster, configured for autoscaling with Horizontal Pod Autoscaling (HPA), and stress-tested for optimal performance.

Tasks
1. Kubernetes Deployment:

Cloned the provided Node.js codebase from the (https://drive.google.com/file/d/12gZcH1Jr1xWWRzyH3yMqJ9DV_3rlHsnK/view?usp=sharing)
Prepared Dockerfiles for containerizing the Node.js application.
Wrote Kubernetes deployment manifests (deployment.yaml) and service manifests (service.yaml) for deployment on a local Kubernetes cluster.

2. Autoscaling with HPA:

Implemented Horizontal Pod Autoscaling (HPA) for the deployed application.
Configured HPA to automatically scale the number of application pods based on CPU usage.

3. Resource Limits and Stress Testing:

Defined resource limitations (CPU and RAM) for the deployed application pods in the deployment manifest.
Used the hey load testing tool to simulate increased traffic and stress the application under load.

4. Monitoring and Documentation:

Recorded a screencast demonstrating the load test execution, showcasing the application scaling up and down in response to changing load.
Captured screenshots for key stages of deployment, autoscaling behavior, and load test results.Autoscaling with HPA:

5. Version Control and Sharing:

Uploaded the complete codebase, including Kubernetes deployment manifests, to a public GitHub repository.
Updated the repository's README.md file with documentation of the project setup, including instructions on running the deployment and load test locally, and links to the video recording and screenshots.

Project Setup
Clone the repository: 
git clone https://drive.google.com/file/d/12gZcH1Jr1xWWRzyH3yMqJ9DV_3rlHsnK/view?usp=sharing
Follow the instructions in the Deployment Guide to deploy the application on a local Kubernetes cluster.
Follow the instructions in the Load Testing Guide to conduct stress testing using the hey tool.


 
 Technologies Used
• Kubernetes
• Node.js
• Horizontal Pod Autoscaler (HPA)
• hey (load testing tool)
