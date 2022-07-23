## MariaDB

This example provides a base setup for using [MariaDB](https://mariadb.org/).

## Configuration

Take a look at the [.env](.env) file and configure it according to your needs or leave it with the defaults.

- MARIADB_ROOT_PASSWORD

## Connection

| Option   | Environment Variable  | Default Value |
| -------- | --------------------- | ------------- |
| Host     |                       | localhost     |
| Port     |                       | 3306          |
| Username |                       | root          |
| Password | MARIADB_ROOT_PASSWORD | mariadbpw     |

## Dial it

Change the current working directory to [./mariadb](.) and run this command:

```shell
docker-compose up
```

Alternatively, from the [root](/../../) directory run:

```shell
docker-compose --project-directory ./mariadb up
```
