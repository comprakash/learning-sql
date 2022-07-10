# Learning SQL
Learning SQL using PostgreSQL

## Install latest PostgreSQL and Azure Data Studio
- [https://www.postgresql.org/download/](https://www.postgresql.org/download/)
- [https://azure.microsoft.com/en-us/services/developer-tools/data-studio/](https://azure.microsoft.com/en-us/services/developer-tools/data-studio/)

## Setup Sample Database

### Sakila Sample Database
- Download the sql files from https://github.com/jOOQ/sakila/tree/main/postgres-sakila-db to the current directory
- `psql -c 'CREATE DATABASE sakila;' -U postgres`
- `psql -d sakila -f .\postgres-sakila-schema.sql -U postgres`
- `psql -d sakila -f .\postgres-sakila-insert-data.sql -U postgres`

### AdventureWorks Sample Database
Click on this link [https://github.com/lorint/AdventureWorks-for-Postgres](https://github.com/lorint/AdventureWorks-for-Postgres) and follow the steps to set up the sample database. 
