# 禁煙bot

## 環境構築

### リポジトリをローカルにコピー

事前にgitをインストールしてください

[Gitのインストール](https://git-scm.com/book/ja/v2/%E4%BD%BF%E3%81%84%E5%A7%8B%E3%82%81%E3%82%8B-Git%E3%81%AE%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)

- リポジトリのクローン

```sh
git clone git@github.com:yach36/kinen_bot_django.git ~/www/kinen_bot_django
```

### コンテナの起動

事前にDockerをインストールしてください

[Docker の入手](https://matsuand.github.io/docs.docker.jp.onthefly/get-docker/)

- 起動

```sh
cd ~/www/kinen_bot_django/docker
docker compose up -d
```

- python が正常にインストールされているか確認

```sh
docker exec -it kinen_bot_python python -V
```

### mysqlにデータを投入

-

## 実行

-
