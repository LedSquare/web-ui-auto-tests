FROM nginx:1.17-alpine

COPY ./docker/prod/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf

RUN apk --no-cache add bash

WORKDIR /site


