FROM docker.io/ubuntu:14.04
MAINTAINER theseaofstars "theseaofstars@live.cn"
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Hi, this is a test from wu' > /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["nginx","-g","daemon off;"]
