# Postgis service

Docker Image for PostgreSQL with PostGIS server and database.
**NB this image is not used in the hosted Kubernetes environment on Azure (PDOK) as there is already a hosted PG service there**

## Hosting

The Docker Image is hosted as: [smartemission/se-postgis at DockerHub](https://hub.docker.com/r/smartemission/se-postgis).
Image version numbers include the PostgreSQL-PostGIS-SE versions. E.g. `9.4-2.1-1` denotes
PostgreSQL 9.4, PostGIS 2.1 and SE build number 1.

## Environment

This image is based on [Kartoza's PostGIS Image](https://github.com/kartoza/docker-postgis). See details
for env vars, overlaying and settings there.

## Architecture

This image is based on [Kartoza's PostGIS Image](https://github.com/kartoza/docker-postgis) with some additional
setting.


## Links

* SE Platform doc: http://smartplatform.readthedocs.io/en/latest/
* Kartoza's PostGIS Image: https://github.com/kartoza/docker-postgis)
