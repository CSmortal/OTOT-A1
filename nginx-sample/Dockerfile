FROM nginx:latest
WORKDIR /etc/nginx/conf.d
COPY default.conf .
WORKDIR /usr/share/nginx/html
COPY my_index.html .
EXPOSE 8080