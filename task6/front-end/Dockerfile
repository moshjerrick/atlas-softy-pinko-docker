# Using nginx as parent image
FROM nginx:latest

# copying front end files into container /var/www/html/softy-pinko-front-end
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copying the Nginx config file into the container at /etc/nginx/conf.d/default.conf
COPY ./softy-pinko-back-end.conf /etc/nginx/conf.d/default.conf