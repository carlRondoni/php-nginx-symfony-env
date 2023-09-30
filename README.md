# PHP Symfony Env

Since my beginnings as a Back End engineer (around 2016), PHP was my first opportunity to get into this branch of programming.

This project is a bit about the skills and packages that I have been working with throughout all this time as a PHP developer.

# Commands

`docker compose up -d`

Access php container:

`docker exec -ti php8-container bash`

# TASKS

- add php lints (phpcs and phpcbf) to follow good standards
- trigger lints on any action before commit (pre commit hook)
- example DDD structure on src folder
- phpunit test enviroment
- phpunit Unit tests
- phpunit Integration tests
- change php:8-fpm image to be alpine updating how the packages are installed on the system
- change php:8-fpm-alpine to be alpine-slim