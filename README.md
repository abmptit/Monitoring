# Monitoring

Project for web Api monitoring

The purpose of this project is to create a monitoring dashboard on web api.

We will use :

## Presentation

### Grafana

### InfluxDB

### Elasticsearch

## How to launch it

Install Docker Desktop for windows :
https://hub.docker.com/editions/community/docker-ce-desktop-windows

execute the following commands :

Open Powershell command windows :

git clone https://github.com/abmptit/Monitoring.git

cd Monitoring

**docker** stop $(docker ps -aq)

**docker-compose** build

**docker-compose** up -d

Open chrome browser :

Navigate to :

Grafana http://localhost:3000/

Elasticsearch http://localhost:9200/
