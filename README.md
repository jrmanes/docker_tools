# Docker Tools

Some useful resources for docker.

- PostgreSQL
  - Create a PostgreSQL server and start a the container PgAdmin.
  - Access to the console:
    - Build the container.
    - Access to: http://localhost:5050
    - The user and password is in the ENV vars.

- Redis

---

## Requirements
- [x] Docker installed
- [x] Docker Compose installed

---

## How to setup

- First, go to the folder that you want to setup.
- Only first time, execute: `docker-compose up --build`
- After, simply execute: `docker-compose up`
- If you want it to run in the background: `docker-compose up -d`

---

Jose Ramon Mañes
