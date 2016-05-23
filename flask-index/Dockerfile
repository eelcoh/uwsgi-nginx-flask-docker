FROM python3-uwsgi-nginx-flask

# forked from 
# MAINTAINER Sebastian Ramirez <tiangolo@gmail.com>

MAINTAINER Eelco Hoekema <ehoekema@gmail.com

# Add app configuration to Nginx
COPY nginx.conf /etc/nginx/conf.d/

# Copy sample app
COPY ./app /app
