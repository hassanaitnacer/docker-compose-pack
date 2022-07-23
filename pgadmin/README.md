## PostgreSQL

This example provides a base setup for using [pdAdmin](https://www.pgadmin.org/).

## Dial it

> This service depends on `postgres`, so before you go, make sure you've followed [these instructions](/../../postgres).

Change the current working directory to [./pgadmin](.) and run this command:

```shell
docker-compose up
```

Alternatively, from the [root](/../../) directory run:

```shell
docker-compose --project-directory ./pgadmin up
```

Open http://localhost:5050

> Use your IP address instead of `localhost` as the hostname if you are unable to connect.
