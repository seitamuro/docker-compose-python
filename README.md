# 概要

Pythonの実行環境をDocker上に実装します｡

# 実行方法

```
$ docker-compose build # イメージの作成
$ docker-compose up -d # コンテナの起動
$ docker exec -it python3 python sample.py # sample.pyの実行｡python3はコンテナ名であることに注意｡
```
