*This README is Work-In-Progress*


# docker-multihost
A repository for showcasing how to host multiple web services on a single physical server using docker containers.

It consists mainly of a collection of docker-compose files that works together to provide the different services.
The main technology behind this is jwilder's nginx-proxy. You can learn more about it here: https://github.com/jwilder/nginx-proxy


## Proxy
nginx-proxy uses subdomain names to determine which container must handle the request.
The whole service is HTTPS encrypted using the nginx-proxy companion (https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion) 

## Web services
### Nextcloud
### Collabora
### OnlyOffice
### Transmission
### Deluge
### Etherpad
