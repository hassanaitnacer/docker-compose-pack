## PostgreSQL

This example provides a base setup for using [PostgreSQL](https://www.postgresql.org/).

## Configuration

Take a look at the [.env](.env) file and configure it according to your needs or leave it with the defaults.

- POSTGRES_PW

## Connection

| Option   | Environment Variable | Default Value |
| -------- | -------------------- | ------------- |
| Host     |                      | localhost     |
| Port     |                      | 5432          |
| Username |                      | postgres      |
| Password | POSTGRES_PW          | postgrespw    |

## Dial it

Change the current working directory to [./postgres](.) and run this command:

```shell
docker-compose up
```

Alternatively, from the [root](/../../) directory run:

```shell
docker-compose --project-directory ./postgres up
```
