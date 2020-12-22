# Todo List

This is a simple project for learning Docker 🐳.

The project combines several services:
* [Todo List App](https://github.com/paulcervov/todo-list-app) - application service
* [Todo List Api](https://github.com/paulcervov/todo-list-api) - backend service
* [Todo List Db](https://github.com/paulcervov/todo-list-db) - mysql database service

Thanks to Docker and Docker Compose, you can quickly deploy and run it all together! 👏

## Deploy

1. `git clone https://github.com/paulcervov/todo-list.git && cd todo-list`

2. `cp .env.example .env`

3. fill `.env` file

4.
    ```
    git clone https://github.com/paulcervov/todo-list-api.git api && \
    git clone https://github.com/paulcervov/todo-list-db.git db && \
    git clone https://github.com/paulcervov/todo-list-app.git app
    ```
5. `docker-compose up -d`

6. `docker-compose logs -f`

Wait until all services are running, then go to the browser.

To stop all services enter `docker-compose down`.

Note: you may need to run `docker-compose` with `sudo`.
