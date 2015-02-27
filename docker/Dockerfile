FROM ubuntu:14.04

MAINTAINER Synapse <synapse791@gmail.com>

RUN apt-get install -y \
        software-properties-common \
        && \
    apt-get update && \
    add-apt-repository ppa:nginx/stable && \
    apt-get update && \
    apt-get install -y \
        nginx \
        && \
    rm -Rf /usr/share/nginx/html/*

ADD nginx.conf /etc/nginx/nginx.conf

CMD ["nginx"]