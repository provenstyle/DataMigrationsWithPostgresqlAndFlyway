
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