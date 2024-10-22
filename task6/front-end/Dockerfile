# start with the latest version of nginx
FROM nginx:latest

# copy files in the directory to container
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# copy the nginx configuration file into the container
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf