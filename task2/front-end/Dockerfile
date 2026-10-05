# Use the latest Nginx image
FROM nginx:latest

# Copy the front-end static files to the specified directory
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the Nginx config file to overwrite the default configuration
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
