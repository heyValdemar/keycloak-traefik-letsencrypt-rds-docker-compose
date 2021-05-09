# Keycloak with Amazon RDS and Let's Encrypt in a Docker Compose

Install the Docker Engine by following the official guide: https://docs.docker.com/engine/install/

Install the Docker Compose by following the official guide: https://docs.docker.com/compose/install/

Deploy Keycloak server with a Docker Compose using the command:

`docker-compose -f keycloak-traefik-letsencrypt-rds-docker-compose.yml -p keycloak up -d`
