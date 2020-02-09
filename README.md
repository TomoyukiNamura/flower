# flower
シリアルナンバー管理ツール

## dockerコンテナコマンド集

dockerコンテナ構築&起動
```
$ cd /path/to/project-X
$ docker-compose up -d
```

dockerコンテナへのログイン
```
(コンテナが起動した状態で)
$ docker exec -it mysql /bin/bash

(ログアウトはコンテナ内で)
# exit
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

