# Postgresql powered by compose


## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd compose-postgres`
* Run this command `docker compose up -d`


## Environments
This Compose file contains the following environment variables:
* `POSTGRES_USER`
* `POSTGRES_PASSWORD`

## Configuration on start
`docker-entrypoint-initdb.d` is a directory with .sql files. All the scripts in that directory will be executed on start of the container.

Therefore, if you want to add a new database, user, or table, you can add a new `.sql` file to that directory.

## Access to postgres: 
* `localhost:6001`

