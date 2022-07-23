## Mongo-Express

This example provides a base setup for using [Mongo-Express](https://github.com/mongo-express/mongo-express).

## Configuration

Take a look at the [.env](.env) file and configure it according to your needs or leave it with the defaults.

- ME_CONFIG_MONGODB_SERVER
- ME_CONFIG_MONGODB_ADMINUSERNAME
- ME_CONFIG_MONGODB_ADMINPASSWORD

## Dial it

> This service depends on `mongo`, so before you go, make sure you've followed [these instructions](/../../tree/main/mongo).

Change the current working directory to [./mongo](.) and run this command:

```shell
docker-compose up
```

Alternatively, from the [root](/../../) directory run:

```shell
docker-compose --project-directory ./mongo up
```

Open http://localhost:5051

> Use your IP address instead of `localhost` as the value of `ME_CONFIG_MONGODB_SERVER` if you are unable to connect.
