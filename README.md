# What's cms ?

cms is Cloud Management system.

Simple of simple.

## Components

```mermaid
graph LR
    A[frontend\nVue.js] <-->|API| B[backend\nJavaScript]
    B <--> C[(PostgreSQL)]
```

gnsnghm/cloud-management-system

https://hub.docker.com/r/gnsnghm/cloud-management-system

gnsnghm/cloud-management-backend

https://hub.docker.com/r/gnsnghm/cloud-management-backend

PostgreSQL 16

https://hub.docker.com/_/postgres

## Required

- Docker
- Docker Compose

## Instllation

```shell
git https://github.com/gnsnghm/cms.git
cd cms
docker compose up -d
```

Access to `http://localhost`

## Environments

### Frontend

`PORT` Change port.

`REACT_APP_API_URL` Backend URL.  
If backend url is `http://localhost:3001/api`,  
`React_APP_API_URL` is `localhost:3001`

### Backend

`DB_HOST` Hostname

`DB_USER` Connect user

`DB_NAME` Database name

`DB_PASSWORD` User password

`DB_PORT` Database port
