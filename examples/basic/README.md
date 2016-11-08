# Basic docker-compose

This docker-compose.yml file builds local image and runs it.

Ports:
- Web: 8080
- Icecast2: 8000

Defaults:
- login: admin
- password: admin

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