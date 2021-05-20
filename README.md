Try https://github.com/dai65527/go_simpleREST with https://github.com/dai65527/tstodo-client using docker-compose.

### clone

```
$ git clone --recursive https://github.com/dai65527/todo_compose
```

### .env
add ./database/.env like below.

```
MYSQL_ROOT_PASSWORD=password
MYSQL_DATABASE=todouser
MYSQL_USER=todoapi
MYSQL_PASSWORD=todopass
TZ=Asia/Tokyo
```

### run

```
$ docker-compose up
```
