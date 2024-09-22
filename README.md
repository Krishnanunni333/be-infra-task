# Backend Infra Task

The task is to run the APIs written in nestjs in seperate container and expose them using a reverse proxy via a single domain (localhost).

## Pre-requisites
1. Docker

## How to run ?
1. Clone this repo
2. CD into cloned repo```cd be-infra-task```
3. Run ```docker compose up```

All the APIs will be available in localhost or localhost:80.

## Links used for developing
1. https://www.tomray.dev/nestjs-docker-production
2. https://umasrinivask.medium.com/configure-nginx-as-a-reverse-proxy-with-docker-compose-file-4ebba2b75c89