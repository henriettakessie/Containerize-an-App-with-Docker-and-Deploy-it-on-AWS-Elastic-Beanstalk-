# Containerize-an-App-with-Docker-and-Deploy-it-on-AWS-Elastic-Beanstalk-
Containerize an App with Docker and Deploy it on AWS Elastic Beanstalk 

In this project, we will first install docker and use it to create containers and then we will create our custom container image. Last, we will deploy our containerized application to the cloud using Amazon elastic Beanstalk.

Docker was successfully installed.

What is the difference between Docker and Docker Desktop?

Docker is a platform for ceating and working with containers whilst Docker desktop is a tool that makes the use of Docker easy.

What is the Docker Daemon?

The docker Daemon is like the engine for docker that receives commands we set through clients. eg clients in the docker desktop or text commands sent in the terminal and actually creates/manages/controls the containers.


Run a pre- built container image-- Step 2
In this step, I created a container using a container image ie. a template for containers.

Build your custom image.--Step 3
In this step we are writing an instruction for how to build our own custom image and tell docker to read the file and  build the container image.

RUN A CONTAINER WITH YOUR CUSTOME IMAGE-- Step 4
In this step, we run the custom image so that we can see the webpage in action.

AN ERROR OCCURED. 
WHAT WAS THE ERROR YOU RAN INTO?

There was an error when I ran my custom image because we tried to map our port 80 with the new container's port 80 but a running container was already using port 80.
I resolved this by stopping the running container so that we can start our new one.


DEPLOY YOUR CUSTOM IMAGE TO ELASTIC BEANSTALK--Step 5
In this step, we are going to set up an application in beanstalk which will help us deploy our web app and make it available to the world.

It took me about one and a half hour to complete this project.



















