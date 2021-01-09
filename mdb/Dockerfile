FROM mariadb:latest

MAINTAINER Siva <siva@gmail.com>

ENV MYSQL_ROOT_PASSWORD=root

ENV MYSQL_DATABASE=mydb

RUN apt-get update && apt-get install -y git

RUN git clone https://github.com/sivadarshan0/dbdump.git /docker-entrypoint-initdb.d/
