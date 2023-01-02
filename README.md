# Postgresql & PgAdmin powered by compose


## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd compose-local`
* Run this command `docker-compose up -d`


## Environments
This Compose file contains the following environment variables:

* `POSTGRES_USER` the default value is **postgres**
* `POSTGRES_PASSWORD` the default value is **postgres**
* `PGADMIN_PORT` the default value is **5050**
* `PGADMIN_DEFAULT_EMAIL` the default value is **admin@pg.com**
* `PGADMIN_DEFAULT_PASSWORD` the default value is **admin**
* `MONGO_INITDB_ROOT_USERNAME` the default value is **admin**
* `MONGO_INITDB_DATABASE` the default value is **auth**
* `MONGO_INITDB_ROOT_PASSWORD` the default value is **pass**
* `ME_CONFIG_BASICAUTH_USERNAME` the default value is **admin**
* `ME_CONFIG_BASICAUTH_PASSWORD` the default value is **pass**
* `MONGOEXPRESS` the default value is **8081**

## Access to postgres: 
* `localhost:5432`
* **Username:** postgres (as a default)
* **Password:** postgres (as a default)

## Access to PgAdmin: 
* **URL:** `http://localhost:5050`
* **Username:** admin@pg.com (as a default)
* **Password:** admin (as a default)

## Add a new server in PgAdmin:
* **Host name/address** `postgres`
* **Port** `5432`
* **Username** as `POSTGRES_USER`, by default: `postgres`
* **Password** as `POSTGRES_PASSWORD`, by default `postgres`

## Access to mongo: 
* `localhost:27017`
* **Username:** admin (as a default)
* **Password:** pass (as a default)
## Access to mongo-express: 
* **URL:** `http://localhost:8081`
* **Username:** admin (as a default)
* **Password:** pass (as a default)


