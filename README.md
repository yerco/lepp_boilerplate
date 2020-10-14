# README.md

Boilerplate template to develop apps.

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
