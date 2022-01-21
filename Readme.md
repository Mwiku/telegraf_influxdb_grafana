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
Clone the Git Repository in your prefered directory

Cd into the cloned directory then run 
docker-compose up to start the stack 

Grafan can be accesed on port 
https; 192.168.10.105:3030 on 