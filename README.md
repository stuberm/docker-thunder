# Installation

### Container, volume and network creation

`docker-compose up -d`

### Composer install

`docker exec thunder_php composer install`

### Useful commands

**List the contents of the NGINX root**

`docker exec thunder_nginx ls web`

**List the contents of the PHP root**

`docker exec thunder_php ls web`

**Add php library via composer**

`docker exec thunder_php composer require monolog/monolog`

**Composer install**

`docker exec thunder_php composer install`