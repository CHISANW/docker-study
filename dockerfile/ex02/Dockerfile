FROM ubuntu

#우분투에서 실행되는 멸령어
RUN apt-get update
RUN apt-get install -y nginx

WORKDIR /var/www/html

COPY webapp/index.html ./index.nginx-debian.html

ENTRYPOINT ["nginx", "-g", "daemon off;"]