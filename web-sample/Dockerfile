# my first docker image
FROM ubuntu
RUN apt-get update && apt-get install -y nginx
RUN echo 'Hi, I am running from container' \
	>/usr/share/nginx/html/index.html
EXPOSE 80
