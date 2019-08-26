# ChaosTest-ParityEthereum

## The Methodology
We are using Docker containers based parity installations preferrably posdao-test-setup and then using an open source tool called DPumba to do Chaos testing on these containers

## Docker Containers
The Dcoker container will be a multistage container that will build parity in the first stage and install all the development tools. And in the second stage it will just copy the parity binary and setup the posdao-test-setup

## DPumba
We need to install DPumba and then a series of scripts are provided to do various kinds of chaos testing on the running docker posdao-test-setup

On MacOS 
brew install pumba

## Steps

## Install Docker
On MacOS
Download the Docker for Desktop for Mac from DockerHub
Once the .dmg file is downloaded, click and install it. Follow the instructions.
Then open a command line to check
docker version
if you get a reply, then docker has been installed properly
docker 

### Run Docker script to build parity

### Setup Docker Container for Parity

### Install Pumba

### Run Docker container

### Run Pumba scripts to test
