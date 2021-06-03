FROM ubuntu

FROM nginx:latest
RUN apt-get update
RUN apt-get install -y git
COPY ./Docker/ /usr/share/nginx/html

EXPOSE 80
EXPOSE 443




