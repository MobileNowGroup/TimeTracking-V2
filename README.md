<p align="center"><img src="http://res.cloudinary.com/guorenjun/image/upload/v1531809978/MN_LOGO_3.png" width="300"></p>

## About This Project

TimeTracking project based on https://github.com/kevinpapst/kimai2.


### Requirements
- Git
- Docker
- PHP
- Mysql

### Startup docker container
```shell
docker-composer up -d
```

### Install dependency packages
```shell
docker-compose exec workspace bash
```

```shell
composer install
```



### Setup configuration
```shell
cp .env.dist .env
```

### Site
localhost:7000