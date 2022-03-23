# kaggleのpython環境をベースにする
FROM gcr.io/kaggle-images/python:v100

# ライブラリの追加インストール
RUN pip install -U pip && \
    pip install fastprogress japanize-matplotlib && \
    pip install mlflow && \
    export DISPLAY=192.168.10.101:0.1
