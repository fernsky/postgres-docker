# postgres-docker
Spin off a PostgreSQL container with persistent data storage.

## Getting started

```
cp .env.sample .env
```

Set the environment variables at `.env`.

- `POSTGRES_DB` : The name of the database. Default `postgres`
- `POSTGRES_USER` : The database user. Default `postgres`
- `POSTGRES_PASSWORD` : Pasword for this database user. Default `postgres`
- `POSTGRES_PORT` : Port via which PostgreSQL container should be exposed externally.Default `5432`.

Start the container.

```
docker-compose up -d
```

Data is stored at `.dbdata`.