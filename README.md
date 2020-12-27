# Todo List

This is a simple project for learning Docker 🐳.

Inspired by [Docker Getting Started Tutorial](https://github.com/docker/getting-started).

The project combines several services:
* [Todo List App](https://github.com/paulcervov/todo-list-app) - application service
* [Todo List Api](https://github.com/paulcervov/todo-list-api) - backend service

Thanks to Docker and Docker Compose, now you can quickly setup and run it all together 👏!

## Setup and run with Docker Compose

1. `git clone https://github.com/paulcervov/todo-list.git && cd todo-list`

2. `cp .env.example .env`

3. fill `.env` file

4. `docker-compose up -d`

5. `docker-compose logs -f`

Wait for all services to load.

To stop all services enter `docker-compose down`.

Note: you may need to run `docker-compose` with `sudo`.
