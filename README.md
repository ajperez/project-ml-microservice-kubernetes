![CircleCI](https://circleci.com/gh/ajperez/project-ml-microservice-kubernetes.svg?style=svg&circle-token=9a695e5591600792671f4c0eb186031b7d40da8b)
# Operationalize a Machine Learning Microservice API
Autor: Antonio J. Pérez Montilla
## Project description
In this project, you will apply the skills you have acquired in this course to operationalize a Machine Learning Microservice API.

You are given a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on the data source site. This project tests your ability to operationalize a Python flask app—in a provided file, app.py—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

## Instructions

### 1. Setup
Create enviroment

run "make install"

### 2. Run application

python app.py --> run application directly  

./run_docker.sh --> run application from docker

./run_kubernetes.sh --> run application from kubernetes.sh

### 3. Upload docker image

./upload_docker.sh --> upload docker image to docker hub 

### 4. Make prediction

1.- Runs docker or kubernetes in a terminal

2.- Open other terminal and run: ./make_prediction.sh

