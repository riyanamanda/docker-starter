### Docker Compose Starter

#

Choose the stack that you want to run and <i>copy</i> it to the root path.

```
cp ./docker/example/lemp-docker-compose.yml ./docker-compose.yml
```

Change the names of the variables in the <i>.env</i> file according to your application requirements.

```
APP_NAME=example_app

DB_NAME=example_db
DB_USER=root
DB_PASSWORD=secret
```

Run <i>docker compose</i> command to start build your containers.

```
docker compose up -d
```

Open web browser and type <i>http://localhost</i> or <i>http://127.0.0.1</i> to access the server. <br/>
Access <i>phpmyadmin</i> on port: 8080 by default.
