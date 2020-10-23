# ベースとなるイメージの指定
FROM python:3.9

# 変数定義
ARG APP_PATH=/code

RUN apt-get -y update && \
    apt-get -y install vim

# pip
# pipの最新化
RUN /usr/local/bin/python -m pip install --upgrade pip
WORKDIR $APP_PATH

# requirements.txt
COPY requirements.txt $APP_PATH/
RUN pip install --no-cache-dir -r $APP_PATH/requirements.txt
