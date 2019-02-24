ELK Containers 6.5.4

This docker compose file mimics cluster of elastic nodes to setup a dev or simulation environment runnin in docker. Each service is assigned with a static ip address for easy internal binding and discovering each other during build up.

Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

Prerequisites
docker

Steps after pulling this repo
1. Run git clone https://github.com/ronelcoe/elk_6.5.4.git
2. To build the container service for the first time, run docker-compose up 
3. To start/stop the service (succeeding run), go to the location of compose file and run docker-compose start/stop
