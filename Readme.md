## Pre-requisites 
1. Ubuntu machine running the latest Ubuntu version, at the time of this writing, 21.10 (Impish indri)

2. Docker
   
 - You can follow the guide provided in the link to install docker
https://docs.docker.com/engine/install/ubuntu/

3. Docker compose
   
  - To install docker-compose, simply run:
  
  `sudo apt install docker-compose`

The setup comprises of two main files:
1. The docker-compose file, which includes all the services required in the stack 
   i.e Telegraf,InfluxDb and Grafana

2. The telegraf specified the metrics that shoud be measured and save in the Influx database


## Getting started
Clone the Git Repository to your prefered directory
`git clone https://github.com/Mwiku/telegraf_influxdb_grafana.git`

Cd into the cloned directory then run 
`docker-compose up` to start the stack


When you are running the stack for the first it might take some time to download the docker images depending on your network speed.

Once everything is up and running go the url http://localhost:3000/login in your browser to log in to grafana


The default username is *sudo* and the password *textig22#*.

You will be prompted to change the password on initial login.