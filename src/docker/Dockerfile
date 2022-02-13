FROM buster

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
