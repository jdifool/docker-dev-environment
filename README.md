# docker-dev-environment

> Disclaimer: This repository is meant for setting up a simple, local php development environment. __Do not use it in production!__

0. Prerequisites

- Basic understanding on how docker works, what containers are and what docker-compose.yml files are for.
- Docker (and docker compose) is installed on your host machine and running.
- No application on your host system is using or blocking port 80 (and/or 443, in case you're going to use https). For example if you use mamp/xamp or such, close those applications first, before proceeding.

1. Run nginx-proxy container


```
cd nginx-proxy
docker compose up -d
```
