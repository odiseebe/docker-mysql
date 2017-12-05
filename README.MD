# Custom configuration for MySQL base

## Description
Custom configuration dockerfile for MySQL base for local development purpose

## Specifications
### The base container
* MySQL (https://hub.docker.com/_/mysql/)
### Addon with this dockerfile
* mysql.cnf

## How to use
### Configuration variables
* VOLUME (/var/www/html)
* PORTS (80)

### Example
docker run -ti -p 8080:80 -v /host/path:/var/www/html --name test-base odisee/web-base-php7-ldap