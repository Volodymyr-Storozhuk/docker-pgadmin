# run pgadmin in docker

[pgadmin in docker hub](https://hub.docker.com/r/dpage/pgadmin4)  
[pgadmin](https://www.pgadmin.org/docs/pgadmin4/latest/container_deployment.html)

### For successful run pgadmin add to .env file yuor variables ###

PGADMIN_DEFAULT_EMAIL=  
PGADMIN_DEFAULT_PASSWORD=

Run command:
```
docker compose --profile dev up -d
```

