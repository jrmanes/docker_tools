# Nginx - Basic Auth

## Description

This folder contains some files for setting up a nginx with basic auth.

This is can be useful if you need to setup a simple basic auth in your server.

## Requirements

- docker
- docker-compose
- htpasswd

## How to use it?

You need to have installed `docker-compose` and execute the following command.

```bash
docker-compose up -d
```

If you want to see the logs, remove the flag `-d`
```bash
docker-compose up
```

## Create a user

```bash
htpasswd auth/nginx.htpasswd <your-user>
# example
htpasswd auth/nginx.htpasswd test
```
