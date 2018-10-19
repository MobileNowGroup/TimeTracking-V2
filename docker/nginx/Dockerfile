FROM nginx:1.11
RUN echo "Asia/Shanghai" > /etc/timezone && dpkg-reconfigure -f noninteractive tzdata
RUN mkdir /etc/letsencrypt
COPY ./nginx.conf /etc/nginx/conf.d/default.conf

ARG PHP_UPSTREAM_CONTAINER=php-fpm
ARG PHP_UPSTREAM_PORT=9000

EXPOSE 80 443