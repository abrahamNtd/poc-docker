FROM nginx:alpine

RUN apk update && apk add bash

COPY nginx.conf /etc/nginx/nginx.conf

COPY index.html /usr/share/nginx/html/index.html
