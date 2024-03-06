# PHP Symfony Env

Basic Symfony (6.4) Dev Enviroment, just installing Docker on your computer with basic set up for code quality and test suite.

With this env you have something to start work with on a symfony env.

## Req

- Docker
- PHP + Composer (and iconv extension enabled)
- `.env` from `.env.example`

## Commands

Build the app:

`docker compose build`

Run the container:

`docker compose up -d`

Access php container:

`docker exec -ti php8-container bash`

Run a command into the container:

`docker exec php8-container <command>`

### Inside Container

Php code_sniffer (to find problems on your code)

`composer lint:check`

Php Beautifier (to fix a few fixable problems from previous command)

`composer lint:fix`
