# README.md

KISS: basic LEPP boilerplate template to render an *initial* index.php
nginx, postgresql, php

## Checking/Running

```bash
% docker-compose up --build -d  
% docker-compose ps
% docker-compose stop
```

## Connect to postgres container

```bash
% docker exec -ti docker_boilerplate_db_1 psql -U example -W example
```
