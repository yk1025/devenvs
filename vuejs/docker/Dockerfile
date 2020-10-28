FROM node:15-buster

#==================
# 変数定義
#==================
ARG APP_PATH=/code

WORKDIR $APP_PATH

#==================
# モジュール
#==================
RUN apt-get update \
    && apt-get install -y wget vim

#==================
# vue-cli
#==================
RUN npm install -g @vue/cli

#==================
# npm
#==================
# COPY package*.json $APP_PATH/
# RUN npm install
