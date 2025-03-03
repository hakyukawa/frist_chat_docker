#ベースイメージ
FROM node:20-slim

#gitのインストール
RUN apt-get update && apt-get install -y git \
curl \
ca-certificates \
openssh-client \
&& rm -rf /var/lib/apt/lists/*

WORKDIR /usr/src/app