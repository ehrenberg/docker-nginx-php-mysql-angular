# Docker Nginx PHP 8 Mysql 8 Angular 13

Docker Container with
- Nginx Newest
- PHP 8.1
- Mysql 8.0
- Angular 13.3.7
- Memcached
- Clickhouse

## Installation

Run and install development environment

```bash
$ docker-compose up
```

take it down with
```bash
$ docker-compose down
```

## Usage

If Angular isnt running. Try to change host in package.json File

```json
"scripts": {
    "ng": "ng",
    "start": "ng serve --host 0.0.0.0",
    ...
```
## Credentials
All important Credentials
1. MySQL (root)
    * Username:ssp
    * Password: password
    * Database: ssp
2. 

## Ports
You can connect to the systems over these ports:

- Symfony: Port 80
- Angular: Port 4200
- MySQL: Port 3306

## License
[MIT](https://choosealicense.com/licenses/mit/)