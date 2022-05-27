## 1. Introduction

Updated image Eclipse Mosquitto 2.0 for isolated environments. __Anonymous subscriber activated__.

## 2. Requirements

1. [Docker](https://docs.docker.com/get-docker/)

## 3. Docker pull

You can download the full image from [Docker Hub](https://hub.docker.com/) with the following command.

````
docker pull davma/mqtt-conf
````

## 4. Image build

You can run the image build with the following commands

````
git clone https://github.com/davma-io-images/eclipse-mosquitto-conf.git
cd eclipse-mosquitto-conf
docker build -t mqtt-conf .
````

## 5.Documentation and guides

[Eclipse Mosquitto web](https://mosquitto.org/)  
[eclipse-mosquitto official_images](https://hub.docker.com/_/eclipse-mosquitto)
