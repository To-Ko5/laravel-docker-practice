# お手軽 LAMP 環境構築

PHP + Nginx + MySQL

# ファイル置き場

app ディレクトリ配下

# env

ルートに env ファイルを作成する
USERNAME=\***\*
USERPASS=\*\***
DATABASE=\***\*
ROOTPASS=\*\***

# docker を起動する

```
docker-compose up -d

docker stop $(docker ps -q)
```
