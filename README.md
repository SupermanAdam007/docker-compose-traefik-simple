# Simple traefik reverse proxy setup
As example, the simple api endopint will be started and routed with traefik to internet.

## Prerequisites
* docker installed
* docker-compose installed
* pointed domain (YOUR_DOMAIN) to the IP of the server (A - IPv4, AAAA - IPv6) records

## Variables
```
./services/traefik/traefik.toml
```
* users = [login, passwd_password] // credentials for the traefik dashboard
* YOUR_MAIL

```
./docker-compose.yml
```
* YOUR_DOMAIN