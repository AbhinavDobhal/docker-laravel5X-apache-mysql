# docker-laravel5X-apache-mysql
Docker example with Apache, MySql, PhpMyAdmin and Php 7.1

## Prerequisites

* Docker

## How to run app

#### Clone and run

```
$ git clone https://github.com/AbhinavDobhal/docker-laravel5X-apache-mysql.git
$ cd docker-laravel5X-apache-mysql
$ docker-compose up -d
```

#### laravel .env 

```
DB_CONNECTION=mysql
DB_HOST=db(mysql - use db)
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=root
```