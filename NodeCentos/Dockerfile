# Docker File Test
# Builds an Image with all the toys I commonly like

# Centos Node

FROM centos:latest

# Update CentOS 7
RUN yum update -y && yum upgrade -y

RUN yum install -y epel-release
RUN yum install -y nodejs
RUN yum install -y npm
RUN yum install -y sl htop iftop iptraf git ufw tmux

# Global Node Modules 
RUN npm install -g pm2 nodemon http-server
