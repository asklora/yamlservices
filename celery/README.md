# Celery docker compose files

## How to run
- If you need the worker, copy both the docker-compose.yml and the dockerfile to your project folder, and then run `docker compose up`
- If you only need the celery backend, run `docker compose --profile noworker up`
