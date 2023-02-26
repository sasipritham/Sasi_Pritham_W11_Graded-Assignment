# Sykam-Raju-W11_Graded-Assignment
Graded Assignment on Implementing Micro Services


## Objective:
Implementing a microservice using the Python Flask framework on an Ubuntu virtual
machine to serve a machine learning prediction model.

To create a Docker image containing everything needed to run the application: the
application code, libraries, tools, dependencies, and other files and to use the image to run
the application in containers.


## Instructions with Screenshots:

<a href="https://github.com/SykamRaju/Sykam-Raju-W11_Graded-Assignment/blob/main/Screenshots.pdf" class="image fit" target="_blank" rel="noreferrer noopener">Check the complete process with screenshots</a>

## Install Docker on Ubuntu 

#### Install  Docker using the following command

```bash
sudo apt-get install docker.io
```

## To Create a Docker image containing everything needed to run the application 

```bash
sudo docker build -t microservice-breast-cancer-prediction .
```


## To run the micro service on Ubuntu:


#### Run the container


```bash
sudo docker run -p 5000:5000 microservice-breast-cancer-prediction
```


