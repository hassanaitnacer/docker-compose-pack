## MongoDB

This example provides a base setup for using [MongoDB](https://www.mongodb.com/).

## Configuration

Take a look at the [.env](.env) file and configure it according to your needs or leave it with the defaults.

- MONGO_INITDB_ROOT_USERNAME
- MONGO_INITDB_ROOT_PASSWORD

## Connection

| Option   | Environment Variable       | Default Value |
| -------- | -------------------------- | ------------- |
| Host     |                            | localhost     |
| Port     |                            | 27017         |
| Username | MONGO_INITDB_ROOT_USERNAME | root          |
| Password | MONGO_INITDB_ROOT_PASSWORD | mongopw       |

Alternatively, you can directly connect using the connection string below:

```
mongodb://root:mongopw@localhost:27017/
```

## Dial it

Change the current working directory to [./mongo](.) and run this command:

```shell
docker-compose up
```

Alternatively, from the [root](/../../) directory run:

```shell
docker-compose --project-directory ./mongo up
```
