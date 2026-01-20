# pra-laravel-todo

## Setup

cp src/.env.example src/.env
docker compose up -d
docker compose exec app php artisan key:generate
docker compose exec app php artisan migrate

## Access

http://localhost

## Stop

docker compose down

## Requirements

- Docker
- Docker Compose
