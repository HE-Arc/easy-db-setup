# easy-db-setup

Docker-compose file to set up a database and manage it easily.

# Requirements

-   [Docker Engine](https://docs.docker.com/install/)
-   [Docker Compose](https://docs.docker.com/compose/install/)

# How to use it

1. copy the docker-compose.yml to the root of your project
2. update the Database login (default: user=root pwd=root)
3. open a terminal from your root project and run `docker-compose up -d`
4. Go to http://localhost:8081
5. Voilà!

# Commands

-   start the containers : `docker-compose up -d`
-   stop the containers : `docker-compose down`

# Administration

You can see and manage your database at http://localhost:8081
