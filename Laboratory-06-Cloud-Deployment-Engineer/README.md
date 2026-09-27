# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

This laboratory focuses on deploying a private cloud storage environment using Nextcloud, MariaDB, and Docker Compose. The goal is to create a simple two-tier architecture where the Nextcloud application communicates with a separate MariaDB database container.

## Objectives

* Understand two-tier architecture.
* Create a Docker Compose configuration.
* Deploy multiple containers as one application stack.
* Connect Nextcloud with a MariaDB database.
* Access the Nextcloud web interface.
* Practice starting and stopping a multi-container environment.
* Document the deployment process.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```

## Skills Learned

Through this laboratory, I learned how Docker Compose can be used to manage multiple containers as one application stack. I also practiced creating YAML configuration files, connecting application and database containers, using environment variables, and checking the status of deployed services.

## Architecture

The deployment uses two main services:

* **Nextcloud App** - provides the web interface and handles user requests.
* **MariaDB Database** - stores the database information required by Nextcloud.
