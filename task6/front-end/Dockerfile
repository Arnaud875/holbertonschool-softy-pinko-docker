FROM nginx:latest
COPY ./front-end/assets /var/www/html/softy-pinko-front-end/assets
COPY ./front-end/index.html /var/www/html/softy-pinko-front-end
COPY ./front-end/softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
EXPOSE 9000