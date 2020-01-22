# project-X
project-X repository

## dockerコンテナ建て方

dockerコンテナ構築&起動
```
$ cd /path/to/project-X
$ docker-compose up -d
```

dockerコンテナ起動
```
$ cd /path/to/project-X
$ docker-compose start
```

dockerコンテナ停止
```
$ cd /path/to/project-X
$ docker-compose stop
```

dockerコンテナ再起動
```
$ cd /path/to/project-X
$ docker-compose restart
```

dockerコンテナ停止&削除
```
$ cd /path/to/project-X
$ docker-compose down --rmi all -v
```

