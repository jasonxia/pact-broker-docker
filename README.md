# Dockerised Pact Broker
==================

This repository deploys [Pact Broker](https://github.com/bethesque/pact_broker) using lightweight containers using Docker. It will start postgres docker container and [pact broker container](https://github.com/DiUS/pact_broker-docker). Then you can access the Pact Broker API and UI through http://xxx.xxx.xx.xxx, the IP may vary depending on your Docker Host IP, the default IP for docker-machine on MacOS is 192.168.99.100

## Prerequisites

* [Install Docker](https://docs.docker.com/installation/)

## Getting Started
  $ docker-compose up 
