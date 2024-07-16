# 社内グルメ掲載LIFFアプリ　フロントエンドコード


## 環境構築
### Dockerコンテナをビルド&起動
プロジェクトルートにて以下コマンドを実行。
```
$ docker compose up -d --build
```
コンテナ内でViteの開発サーバーが起動します。

### パッケージのインストール
プロジェクトルートにて以下コマンドを実行。
```
$ docker compose run --rm web yarn install
```

### 開発サーバーにアクセス
http://localhost:5173/ にアクセスして画面が表示されることを確認。
