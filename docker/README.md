# init

コンテナー立ち上げ
```
docker compose up -d
```

コンテナー終了
```
docker compose down
```

接続
```
docker exec -it postgres psql -U exampleuser -d todo_db
```