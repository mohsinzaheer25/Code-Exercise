FROM ubuntu:14.04
MAINTAINER Mohsin Zaheer "mohsinmohammed2018@outlook.com"
RUN apt-get update -y && \
    apt-get install -y nginx
WORKDIR /usr/share/nginx/html/
RUN rm index.html
COPY env.sh index.html /usr/share/nginx/html/
RUN /bin/bash env.sh >> env.js
EXPOSE 80