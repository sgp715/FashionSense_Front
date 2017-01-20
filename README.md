# FashionSense Front

## Description
Hosts our NGINX reverse proxy server.

## Install
* [install Docker](https://docs.docker.com/engine/installation/)

## Usage
* to run with Docker
    * first build everything with Docker
    ```
    $ docker build -t front
    ```
    * to run with Docker
    ```
    $ docker run -p 80:80 front .
    ```
