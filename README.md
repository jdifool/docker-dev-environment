# docker-dev-environment

> Disclaimer: This repository is meant for setting up a simple, local php development environment. __Do not use it in production!__

0. prerequisites

- docker (and docker compose) is installed on your host machine and running.
- no application on your host system is using or blocking port 80 (and/or 443, in case you're going to use https).

1. run nginx-proxy container


```
cd nginx-proxy
docker compose up -d
```
