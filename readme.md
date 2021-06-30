# sermoni

Server monitor app

## Using

This project directly working with [docker](https://www.docker.com/).

- [NodeJS](https://nodejs.org)
  - [NestJS](https://docs.nestjs.com) (*backend framework*)

- [MongoDB](https://www.mongodb.com)
  - [mongo-express](https://github.com/mongo-express/mongo-express) (*admin gui*)

- [NGINX](https://www.nginx.com)

## Setup

- First create volume for db `docker volume create mongo-data`

## Default Routes

- app running at: http://localhost:8080
- mongo-express admin login: http://localhost:8081 ([user-pass](./.env))
- 