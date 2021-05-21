# PHP+Apache+MySQL

[URL](tehttps://qiita.com/naente_dev/items/d259ea84c172deeff7d8st)

## How To Use

1. docker 起動
1. コンテナ起動

- docker-compose up -d（初回）
- docker-compose start （二回目以降）

1. アクセス

- localhost:8080
- localhost:4040

1. コンテナ停止

- docker-compose stop

1. コンテナ削除

- docker-compose down
- docker-compose down --rmi all --volumes --remove-orphans（完全消去）

## MySQL Command Line

1. docker exec -it [container_name] bash
1. mysql -u[user] -p[password]
