# Complex docker-compose

This docker-compose.yml file builds local image and runs it.

Ports:
- Web: 8080
- Icecast2: 8000

Defaults:
- login: admin
- password: admin

ENV variables:
- LANG = en_US.UTF-8
- LANGUAGE = en_US:en
- LC_ALL = en_US.UTF-8
- HOSTNAME = localhost

Volumes:


## Build & Start
```
docker-compose up -d
```

## Start
```
docker-compose start
```

## Stop
```
docker-compose stop
```

## Stop and remove containers
```
docker-compose stop && docker-compose rm
```