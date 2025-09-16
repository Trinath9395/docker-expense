#FROM nginx 
FROM node:20.18.3-alpine3.21
RUN rm -rf /usr/share/nginx/html/index.html 
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY code /usr/share/nginx/html 