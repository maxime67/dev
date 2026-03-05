FROM nginx:alpine as build

RUN apt-get update 

COPY index.html styles.css app.js /usr/share/nginx/html/

EXPOSE 80
