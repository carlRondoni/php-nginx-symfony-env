# PHP Symfony Env

Basic Symfony (6.3) Dev Enviroment, just installing Docker on your computer.

## Req

- Docker

### Optional Req

- Vs Code + exts : Docker and Dev Containers [Check NOTE]

NOTE: on VSCode you can access to a container and dev some stuff inside it and it will reflect the changes into the code. Check for setting it up -> https://code.visualstudio.com/docs/devcontainers/containers . After this on open VSC -> Docker (sidebar menu) -> right click on php container and click on 'Attach Visual Studio Code'

## Commands

Build the app:

`docker compose build`

Run the container:

`docker compose up -d`

Access php container if you dont use VSC container dev tool:

`docker exec -ti php8-container bash`
