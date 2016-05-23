FROM python3-uwsgi-nginx:latest

# forked from 
# MAINTAINER Sebastian Ramirez <tiangolo@gmail.com>

MAINTAINER Eelco Hoekema <ehoekema@gmail.com

RUN pip install --upgrade pip
RUN pip install flask

# Add app configuration to Nginx
COPY nginx.conf /etc/nginx/conf.d/

# Copy sample app
COPY ./app /app
