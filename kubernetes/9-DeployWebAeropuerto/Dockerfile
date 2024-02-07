FROM ubuntu
RUN apt-get update
RUN apt-get install -y apache2
COPY webaeropuerto /var/www/html
EXPOSE 80
CMD /usr/sbin/apachectl -D FOREGROUND