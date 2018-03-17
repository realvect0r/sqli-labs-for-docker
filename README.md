# Sqli labs for Docker

Sql injection labs via docker.

## How to use

1. clone this repository.
```bash
git clone https://github.com/realVEct0r/sqli-labs-for-docker
```
2. edit config in `.env`. (optional)
3. run it!
```bash
docker-compose up
```
4. update mysql account in `code/sqli-labs/sql-connections/db-creds.inc`.
```php
<?php
//give your mysql connection username n password
$dbuser ='root';
$dbpass ='root';
$dbname ="security";
$host = 'db';
$dbname1 = "challenges";
?>
```
5. enjoy it!

## Tip
1. You can view/edit valnerable code in `code/sqli-labs`.
2. You can connect mysql server on port `8989`.