# Data Migrations with Postgresql and Flyway

## Workflow
    docker compose up -d
    docker attach flyway
    flyway migrate 
    docker compose down

## Flyway Database Migrations Commands

    flyway info
    flyway migrate
    flyway clean

## Postgres
Default Username: postgres


## Helpful links

* https://documentation.red-gate.com/fd/quickstart-docker-205226373.html
* https://jdbc.postgresql.org/documentation/use/
* https://www.pgadmin.org/
* https://docs.docker.com/compose/compose-file/05-services/
* https://docs.docker.com/engine/reference/commandline/attach/
* https://stackoverflow.com/questions/34658836/docker-is-in-volume-in-use-but-there-arent-any-docker-containers
