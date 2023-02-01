# docker-nest

Docker を使用して nest.js の環境構築を行います。
以下の手順でローカル環境で nest.js サーバーが立ち上げることができます。
Image や Volume は以下手順で取得できるのでコミットしていません。

フォルダ作成

```
mkdr nest-volume
```

コンテナ立ち上げ

```
docker compose up -d
```

以下にアクセスします。

```
http://localhost:3000/
```
