# postgres / pgAdmin

## Defaults

See [.env](./.env) file for the defaults

## Start

```shell
docker-compose up -d
```

## Stop

```shell
docker-compose down
```

## Stop / Clean

```shell
docker-compose down -v
```

## Links

[pgAdmin](http://localhost:8003/)

## References

Shell scripting in docker-compose.yml and permission changing of the `pgpassfile` inspired by the following repo
[asaikali / docker-compose-postgres](https://github.com/asaikali/docker-compose-postgres)
