# Automated CI/CD Pipeline for Django Web Application using AWS, Docker , Jenkins and Kubernetes.


## Introduction:

Building a robust and efficient CI/CD pipeline for a Django web application can be a challenging task. However, with the right tools and techniques, it can be streamlined and automated, ensuring that your web application is always up-to-date and running smoothly.

In this project, I was created an automated CI/CD pipeline for a Django web application using AWS, Docker, Jenkins, and Kubernetes. I was use AWS to host the web application, Docker to containerize the application, Jenkins to automate the build and deployment process, and Kubernetes to manage the deployment of the application.

The goal of this project is to automate the entire process of building, testing, and deploying a Django web application, ensuring that any changes to the application code are thoroughly tested and deployed to the production environment seamlessly.

I was start by creating a Django web application and containerizing it using Docker. Next, I was configured a Jenkins server and set up a CI/CD pipeline to automate the build and deployment process. Then I was use Kubernetes to manage the deployment of the application, ensuring that it is running efficiently and effectively.

By the end of this project, I have gained valuable experience in automating the build and deployment process for Django web applications and was have a better understanding of how to use AWS, Docker, Jenkins, and Kubernetes to create a robust and efficient CI/CD pipeline.


## The project involves the following steps:

1. Set up an AWS EC2 instance: First, I was created an AWS EC2 instance to host the Django web application. I was configured the instance with the necessary software and tools, including Docker and Kubernetes.

2. Containerize the Django application: Then containerize the Django web application using Docker. I was created a Dockerfile that specifies the application dependencies and build the Docker image.

3. Configure a Jenkins server: I was set up a Jenkins server and configure it to build and deploy the Docker image to the Kubernetes cluster. I was created a Jenkins pipeline that will automate the build and deployment process.

4. Deploy the Docker image using Kubernetes: I was use Kubernetes to manage the deployment of the Docker image. I was created Kubernetes deployment files that define the deployment specifications, including the number of replicas and container resources.

5. Test the deployment: Once the deployment is complete, I was tested the application to ensure that it is functioning correctly. then verify that the website is accessible by visiting the public IP address of the EC2 instance in a web browser.



## Architecture 

<img width="1396" alt="image" src="https://raw.githubusercontent.com/ahmad24mliwala/images/main/To-do-list%20devops%20project%20architecture.png?raw=true">



