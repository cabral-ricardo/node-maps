# Node.js - Working API Google Maps

This application will save geolocation from browsers in MySQL


## Script create data base

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

```
npm install
```
