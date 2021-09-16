# ProjConnect

Here you can find the ProjConnect's documentation
-  [Backend's and Database's](./doc/backend_db/README.md)
-  [Frontend's](./doc/frontend/README.md)

## Docker

### Installation

Follow [Install Docker](https://docs.docker.com/get-docker/) and [Install Docker Compose](https://docs.docker.com/compose/install/) to have all the requiremnts to use the docker-compose file present in this repository.

### Execution

Run the following command to run a mongoDB instance locally, a container and a volume (db data persistency) will be created.
```
docker-compose up -d
```

To remove the container run
```
docker-compose down
```

And to remove the docker volume
```
docker volume rm <name of volume>
```


## mongo shell

In order to interact with mongoDB, [mongo shell](https://docs.mongodb.com/v4.4/mongo/) is recommended.
