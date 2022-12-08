

## Database

### Prerequisite

A Postgres database instance.

### schema_sqlite.sql 

Used to generate the correct inserts against the Postgres database. It is included 
with the kubernetes deployment that periodically extract the data from the clusters.

### schema_postgres.sql 

The schema used to create the centralized Postgres database.
Create with:

```
psql ... < schema_postgres.sql
```
