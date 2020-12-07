# Extending an existing official image from Docker Hub

FROM nginx:latest
# pining the version 

WORKDIR /usr/share/nginx/html
# change working directory to root of nginx webhost
# using WORKDIR is preferred to using 'RUN cd /some/path'

COPY index.html index.html

# No need to specify EXPOSE or CMD because they're in FROM
