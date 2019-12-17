FROM ubuntu2:v1
RUN apt-get update -y && apt-get install apache2 -y 
COPY /home/ubuntu/webfiles /var/www/html
EXPOSE 80
CMD apache2 -DFOREGROUND

