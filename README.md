# Node.js - Working API Google Maps

This application will save geolocation from browsers in MySQL

## Install setting with server using 'restify' 

```
npm install -- save restify
```

## Install setting with database mysql using 'knex'

```
npm install -- save knex
```

## Install database 'mysql' 

```
npm install -- save mysql
```

## Script Create DataBase

```sql
CREATE DATABASE IF NOT EXISTS `db`;
USE `db` ;

CREATE TABLE IF NOT EXISTS `db`.`places` (
  `id` INT(11) NOT NULL AUTO_INCREMENT,
  `place_id` VARCHAR(30) NULL DEFAULT NULL,
  `address` TEXT NULL DEFAULT NULL,
  `image` TEXT NULL DEFAULT NULL,
  PRIMARY KEY (`id`))
ENGINE = InnoDB
```

## Create key google maps 

```
https://developers.google.com/maps/documentation/javascript/get-api-key 
```