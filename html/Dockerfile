FROM ubuntu
RUN apt update -y
RUN apt install apache2 -y
COPY . /root/index.html
CMD [ "/usr/sbin/apachectl", "-D", "FOREGROUND" ]
