FROM ubuntu
RUN apt update && apt install nginx -y
ADD . /var/www/html
CMD nginx -g "daemon off;"
