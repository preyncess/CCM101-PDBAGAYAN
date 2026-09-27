# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block defines the containers that will be created and managed by Docker Compose. In this project, there are two services: `database` for MariaDB and `app` for Nextcloud. Each service contains its own image, settings, environment variables, and other configuration needed for deployment.

## How Does the Nextcloud App Find the Database?

The Nextcloud application uses the `MYSQL_HOST` environment variable to find the database container.

The configuration contains:

```yaml
- MYSQL_HOST=database
```

The value `database` refers to the service name of the MariaDB container. Docker Compose provides internal networking between the services, allowing the Nextcloud container to communicate with MariaDB using the service name.

## `docker run` vs `docker-compose up -d`

The `docker run` command is normally used to create and start an individual container. When several containers are required, multiple `docker run` commands may need to be written and configured separately.

The `docker-compose up -d` command uses the configuration in the `docker-compose.yml` file to create and start multiple related services together. The `-d` option runs the services in the background, allowing the terminal to be used for other commands.
