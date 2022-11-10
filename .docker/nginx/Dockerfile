FROM nginx:stable-alpine

EXPOSE 80

COPY default.conf /etc/nginx/conf.d/
COPY custom.conf /etc/nginx/conf.d/

RUN apk add --update bash && rm -rf /var/cache/apk/*
