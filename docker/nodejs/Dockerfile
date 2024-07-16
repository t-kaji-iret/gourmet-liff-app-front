# 親イメージとしてNode.jsのLTSバージョンを指定
FROM node:20.15.1
# コンテナ内の作業ディレクトリを/appに指定
WORKDIR /app
# ビルド時にコンテナ内でapt-getを更新する
RUN apt-get update -qq
# プロジェクトをコンテナ内にコピー
COPY . .
# 起動時にコンテナ内でViteを起動する
CMD ["yarn", "dev", "--host", "0.0.0.0"]