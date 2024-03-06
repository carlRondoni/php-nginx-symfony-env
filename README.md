# PHP Symfony Env

Basic Symfony (6.4) Dev Enviroment, just installing Docker on your computer with basic set up for code quality and test suite.

With this env you have something to start work with on a symfony env.

## Req

- Docker
- PHP + Composer (and iconv extension enabled)
- `.env` from `.env.example`

## Start

Clone this repo and run `composer install`. After that you can start play with docker.

## Docker Commands

Build the app -> `docker compose build`

Run the container -> `docker compose up -d`

Access php container -> `docker exec -ti php8-container bash`

Run a command into the container -> `docker exec php8-container <command>`

Local Url -> `http://localhost:8080`

## Composer scripts

Remember to start with `composer`:

`lint:check` -> check and display lint errors

`lint:fix` -> check and fix some errors
