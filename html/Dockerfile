FROM ubuntu
RUN apt update -y
RUN apt install apache2 -y
CMD touch index.html
COPY . /root/index.html
CMD [ "/usr/sbin/apachectl", "-D", "FOREGROUND" ]
