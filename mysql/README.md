## MySQL

This example provides a base setup for using [MySQL](https://www.mysql.com/).

## Configuration

Take a look at the [.env](.env) file and configure it according to your needs or leave it with the defaults.

- MYSQL_ROOT_PASSWORD

## Connection

| Option   | Environment Variable | Default Value |
| -------- | -------------------- | ------------- |
| Host     |                      | localhost     |
| Port     |                      | 3306          |
| Username |                      | root          |
| Password | MYSQL_ROOT_PASSWORD  | mysqlpw       |

## Dial it

Change the current working directory to [./mysql](.) and run this command:

```shell
docker-compose up
```

Alternatively, from the [root](/../../) directory run:

```shell
docker-compose --project-directory ./mysql up
```
