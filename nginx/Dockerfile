FROM nginx:stable

RUN rm -rf /docker-entrypoint.d/10-listen-on-ipv6-by-default.sh
RUN apt-get update && apt-get install -y iputils-ping
COPY ./nginx.conf /etc/nginx/nginx.conf

WORKDIR /usr/share/nginx/html
