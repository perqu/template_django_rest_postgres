## Simple Django project with Celery, RabbitMQ, Flower and Postgres

Example of implementations a simple Django app with Postgress DB.

## Docker-compose configuration

- `app`: Django app - Web server
- `postgres`: RDBMS

## How to run the project

1. Clone the repository
2. Install docker
3. install poetry env
4. convert .envexample to .env and update your data
5. Run `docker compose build`
6. Run `docker compose up`
7. Open http://0.0.0.0:8888 in your browser to see the Swagger UI
