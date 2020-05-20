FROM golang:1.13.7-buster

# コンパイルしたファイルの格納場所
ENV GOBIN=/go/src
ENV GO111MODULE=on

# RUN, や ENTRYPOINT などを実行するワークディレクトリを指定
WORKDIR $GOBIN

# 必要なパッケージをイメージにインストールする
RUN apt-get update \
  && apt-get install git
