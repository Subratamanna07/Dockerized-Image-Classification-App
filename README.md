# Follow these instructions to launch it:
	- git clone https://github.com/cloudxlab/Dockerized-Image-Classification-App
	- cd Dockerized-Image-Classification-App
	- docker-compose  build
	- #docker stack deploy -c docker-compose.yml 
	- docker-compose up
	- Open http://e.cloudxlab.com:4114
	
# You can debug it as follows
	- docker ps
	- // Find out the id of model server and use that below
	- docker exec -it 86035cfc3daa python test_client.py
	- // Or you can get the shell inside the docker container as follows
	- docker exec -it 86035cfc3daa bash

# Dockerized-Image-Classification-App

This is the dockerized verion of the project 
project directory for the image classification project using Flask and ZMQ.[Improving the Performance of Deep Learning based Flask App with ZMQ](https://github.com/vagdevik/Flask-ZMQ-App-Folder).


