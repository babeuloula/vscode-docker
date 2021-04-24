# VS Code Docker

VS Code in web browser with Docker. Thanks to [cdr/code-server](https://github.com/cdr/code-server) for docker image.

## Installation

Copy `.env.dist` into `.env`, fill fields and start with `docker-compose up -d`.

The fields `DOMAINS`, `LETSENCRYPT_EMAIL` and `VIRTUAL_PORT` is mandatory if you use [evertramos/nginx-proxy-automation reverse proxy](https://github.com/evertramos/nginx-proxy-automation). It's a powerfull nginx reverse proxy with Let's Encrypt SSL.

## Folders

### config

Your password for VS Code.

### local

Your extensions and user profile.

### projects

All your projects.