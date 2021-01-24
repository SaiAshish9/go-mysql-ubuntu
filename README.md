```

ubuntu-software -> mysql-workbench -> permissions -> allow read , write operations

sudo mysql -u root -p

CREATE USER 'saiashish'@'localhost' IDENTIFIED BY 'saiashish';

GRANT ALL PRIVILEGES ON *.* TO 'saiashish'@'localhost';

CREATE DATABASE IF NOT EXISTS `go-mysql`;

USE `go-mysql`;

SELECT * FROM `go-mysql`.customer;

```