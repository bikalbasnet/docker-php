# Docker PHP Containers
Docker containers built on the top of official PHP containers with addition software installed which makes development fast and easy.
- composer
- git

## Docker Registry
```
docker pull l3ikal/php:7.1.3-fpm
```

## Usage
```
docker run -it --rm --name my-app -v "$PWD":/usr/src/myapp l3ikal/php:7.1.3-fpm
``` 