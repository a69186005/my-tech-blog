# My Technological Blog
## Introduce
### The blog use developed Vue, Bootstrip, Webpack to develop the website's front. The blog's back mode is MVC. It use Python Django, MySQL, Nginx. The whole project runs on docker.
## Install Environment
### Installations
#### 1. Docker
#### Check old Docker and remove it
    $ sudo yum remove docker \
                  docker-client \
                  docker-client-latest \
                  docker-common \
                  docker-latest \
                  docker-latest-logrotate \
                  docker-logrotate \
                  docker-engine
#### Install necessary packages
    $ sudo yum install -y yum-utils \
        device-mapper-persistent-data \
        lvm2
#### Use below orders to set a stable hub
    $ sudo yum-config-manager \
        --add-repo \
        https://download.docker.com/linux/centos/docker-ce.repo
#### Install lastest docker
    $ sudo yum install docker-ce docker-ce-cli containerd.io
#### Start docker
    $ sudo systemctl start docker
#### check your docker
    $ sudo docker run hello-world
### 2. Use docker to install Python, Mariadb, Nodejs, Nginx
#### Install python
    $ docker pull python
#### Install Mariadb
    $ docker pull mariadb
#### Install Node
    $ docker pull node
#### Install Nginx
    $ docker pull nginx

## Deploy