FROM nginx:alpine as build

COPY index.html styles.css app.js /usr/share/nginx/html/

RUN chown nginx:nginx -R /usr/share/nginx/html/

USER nginx

EXPOSE 80
