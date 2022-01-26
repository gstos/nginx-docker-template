# nginx-docker-template

Configuration template for nginx made in Golang Template,
adapted from [nginx-proxy](https://hub.docker.com/r/jwilder/nginx-proxy),
in order to be used alongside with [docker-gen](https://hub.docker.com/r/nginxproxy/docker-gen) and nginx containers.

## Main additions to the original template
This version aims to support raw tcp and udp reverse proxying (via env variable LISTEN_PORT),
as well as TLS termination (adding a cert file). 

## DISCLAIMERS
This is a working in progress repository. 
Breaking changes may occur until we reach a stable version.
Not intended for use in production yet. 
