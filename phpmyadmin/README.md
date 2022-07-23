## phpMyAdmin

This example provides a base setup for using [phpMyAdmin](https://www.phpmyadmin.net/).

## Configuration

Take a look at the [.env](.env) file and configure it according to your needs or leave it with the defaults.

- PMA_HOST

## Authentication

Use `root` as the username and whatever password you set up for [MySQL](/../../tree/main/mysql/.env) or [MariaDB](/../../tree/main/mariadb/.env).

## Dial it

> This service depends on `mysql` or `mariadb`, so before you go, make sure you've followed [these instructions](/../../tree/main/mysql) or [these](/../../tree/main/mariadb).

Change the current working directory to [./phpmyadmin](.) and run this command:

```shell
docker-compose up
```

Alternatively, from the [root](/../../) directory run:

```shell
docker-compose --project-directory ./phpmyadmin up
```

Open http://localhost:5052

> Use your IP address instead of `localhost` as the value of `PMA_HOST` if you are unable to connect.
