FROM docker.io/yujinzhu/hello-world-nginx:latest

USER root

RUN sed -i "s/nginx/v1/g" /usr/share/nginx/html/index.html

USER 1001
