# PHP Symfony Env

Basic Symfony (6.4) Dev Enviroment, just installing Docker on your computer and basic set up for code quality and test suite.

## Req

- Docker

## Commands

Build the app:

`docker compose build`

Run the container:

`docker compose up -d`

Access php container:

`docker exec -ti php8-container bash`

### Inside Container

Php code_sniffer (to find problems on your code)

`composer lint:check`

Php Beautifier (to fix a few fixable problems from previous command)

`composer lint:fix`