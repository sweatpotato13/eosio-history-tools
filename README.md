# EOSIO HISTORY-TOOLS

## Usage

### 0. Set up .env file
```sh
## PostgreSQL
POSTGRES_HOST=ship-postgres
POSTGRES_PORT=
POSTGRES_PASSWORD=
POSTGRES_DB=postgres
POSTGRES_VOLUME=pgdata

## PgAdmin
PGADMIN_PORT=
PGADMIN_DEFAULT_EMAIL=
PGADMIN_DEFAULT_PASSWORD=
```

### 1. Turn on postgres
```sh
docker-compose up -d
```

### 2. Turn on history-tools
```sh
docker-compose -f docker-compose-history-tools.yaml up -d
```

## DONE