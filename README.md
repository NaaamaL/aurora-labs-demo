# aurora-labs-demo

requirements:
  docker, docker-compose installed

How to run the Jenkins server locally on Ununtu 22.04:
* clone the repo
* cd inside
* build the docker image: `docker build -t jenkins/jenkins:lts-with-python3.6 .` (the Dockerfile uses tha latest image of the official jenkins image and install python3.6)
* run docker-compose up
