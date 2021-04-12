FROM nginx:stable
LABEL Name="jatiman-nginx"
LABEL Version="1.0"
LABEL Maintainer="Jati Nurohman (me@jatiman.com)"

RUN mkdir /var/www
COPY ./hello.txt /var/www/
COPY ./default.conf /etc/nginx/conf.d/default.conf