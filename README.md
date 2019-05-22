# Requirements
動作確認済みの環境です。

| | |
|:--:|:--:|
|**OS**|Mac OS Mojave v10.14.4|
|**docker**|version 18.09.2, build 6247962|
|**docker-compose**|version 1.23.2, build 1110ad01|
|**git**|git version 2.20.1|

# Get Started

## 1. リポジトリのクローン
`$ git clone https://github.com/ytskmt14/django-template.git {your_project_name}`

## 2. コンテナを起動
`$ docker-compose up -d`

## 3. runserverの起動
`$ docker container exec -it {web_container_name} python mysite/manage.py runserver 0.0.0.0:8000 --settings config.local_settings`

## 4. ブラウザでアクセス
下記URLにアクセス

http://localhost:8000/