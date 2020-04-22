FROM alpine:latest
RUN apk add --update darkhttpd
RUN mkdir -p /srv/www
COPY index.html /srv/www/index.html
CMD darkhttpd /srv/www --port 8080
