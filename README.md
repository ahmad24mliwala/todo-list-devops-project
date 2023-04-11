# Automated CI/CD Pipeline for Django Web Application using AWS, Docker , Jenkins and Kubernetes.


## Introduction:

Building a robust and efficient CI/CD pipeline for a Django web application can be a challenging task. However, with the right tools and techniques, it can be streamlined and automated, ensuring that your web application is always up-to-date and running smoothly.

In this project, I was created an automated CI/CD pipeline for a Django web application using AWS, Docker, Jenkins, and Kubernetes. I was use AWS to host the web application, Docker to containerize the application, Jenkins to automate the build and deployment process, and Kubernetes to manage the deployment of the application.

The goal of this project is to automate the entire process of building, testing, and deploying a Django web application, ensuring that any changes to the application code are thoroughly tested and deployed to the production environment seamlessly.

I was start by creating a Django web application and containerizing it using Docker. Next, I was configured a Jenkins server and set up a CI/CD pipeline to automate the build and deployment process. Then I was use Kubernetes to manage the deployment of the application, ensuring that it is running efficiently and effectively.

By the end of this project, I have gained valuable experience in automating the build and deployment process for Django web applications and was have a better understanding of how to use AWS, Docker, Jenkins, and Kubernetes to create a robust and efficient CI/CD pipeline.



### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/shreys7/django-todo.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)


## Architecture 

<img width="1396" alt="image" src="https://raw.githubusercontent.com/ahmad24mliwala/images/main/To-do-list%20devops%20project%20architecture.png?raw=true">
