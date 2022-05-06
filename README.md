# Postgres on Docker

## Running the container

```bash
# 5436 port is exposed by default. See the detail in the .env file.
$ bin/start-db
```

## Stopping the container

```bash
# stop docker container.
$ bin/stop-db

# stop and remove docker container.
# also remove volume.
$ bin/stop-db -rv
```

## Modify the env file

```bash
$ vi .env
```
