# Wordpress
Wordpress is built on docker

# PHP 7, Apache docker environment
Docker container with php 7.1 on Apache (httpd). Based on an docker-compose.yml file

# Requirements
- Docker and Docekr-compose
- GIT

# Installation
1. clone this repository `git clone https://github.com/meysam-mahmoodi/docker-wordpress.git`
2. navigate to it `cd docker-wordpress`
3. Build docker image: `docker-compose build`
4. Run it: `docker run -d --name wordpress -p 80:80 docker-wordpress_php7`

