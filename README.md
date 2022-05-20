###### This repo contains a docker compose config to build a Rails 7 full (not api) skeleton app with devise, postgres, vite and vue3


# Guide to Run the Rails base app

Make sure you have installed **[Docker](https://docs.docker.com/get-docker/)**. and **[Docker compose](https://docs.docker.com/compose/install/)**.

Clone the repo

In the root directory, create a folder named **node_modules**

In the root directory, create a **.env** file with the following variables making sure to replace the necessary ones.

- RAILS_ENV="development"

- POSTGRES_DB="db_name"
- POSTGRES_USER="postgres"
- POSTGRES_PASSWORD="postgres"

- UID=1000 (get it in terminal with "id -u" command)
- GID=1000 (get it in terminal with "id -g" command)


Run **docker-compose up** in terminal