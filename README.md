<p align="center"><img width="200" src="https://mjawaid.files.wordpress.com/2017/03/laradock.png?w=820&h=312&crop=1"></p>

## Docker-Compose for Laravel

After much research and struggle this is a configuration of the docker-compose that I got to be able to run my projects in Laravel.

## Prerequisites

- [Docker](https://www.docker.com/).

## Configuration and Use

In the *docker-compose.yaml* file you configure the docker services/containers.

In the *./docker* folder you configure the dependencies (nginx, php) of the docker services/containers.

Run `docker-compose up -d` to raise the containers.

To check the containers by running `docker ps`.

To access the project *[http://localhost](http://localhost)*.

To kill `docker-compose kill` containers.

To remove the `docker-compose rm` containers.