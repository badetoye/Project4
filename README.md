[![circleci](https://circleci.com/gh/badetoye/Project4.svg?style=svg)](https://circleci.com/gh/badetoye/Project4) 

# Operationalize a Machine Learning Microservice API

## Project Summary
This project is about operationalizing a Machine Learning microservice API.
A pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios has been given.

This project tests your ability to operationalize a Python flask app—in a provided file, app.py—that serves out predictions (inference) about housing prices through API calls.

## Project Tasks
Our project goal is to operationalize this working, machine learning microservice using kubernetes, which is an open-source system for automating the management of containerized applications. In this project we:

- Test our project code using linting
- Complete a Dockerfile to containerize this application
- Deploy our containerized application using Docker and make a prediction
- Improve the log statements in the source code for this application
- Configure Kubernetes and create a Kubernetes cluster
- Deploy a container using Kubernetes and make a prediction
- Upload a complete Github repo with CircleCI to indicate that our code has been tested

**Files and Script files**
- app.py - a pre-trained python model which serves the prediction.
- config.yml - a circleci config file contained in the .circleci which describes the steps to run the project in circleci.
- run_kubernetes.sh - a script file which executes the commands to deploy the kubernetes cluster.
- Makefile - describes the environment setup for the project and lints the python and docker files.
- upload_docker.sh - a script file which executes the commands to upload the docker image to dockerhub.
- run_docker.sh - a script file which executes the commands to deploy the docker image.
- Dockerfile - a docker confi file used to build the docker image.
- requirements.txt - a file which specifies the required packages to be installed for the project.

## Environment Setup
- Create a virtualenv & activate it
- Run `make install` to install dependencies
- Setup & configure docker locally
- Setup & configure kubernetes locally
- Run app.py => `python app.py`(standalone)
- Run script in docker => `./run_docker.sh`
- Run kubernetes => `./run_kubernetes.sh`




