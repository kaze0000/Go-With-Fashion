## サービス概要

好きなブランドでマッチングできるサービス

## メインのターゲットユーザー

- 一緒に服を買いにいく友達を探している
- 好きなブランドについて語り合いたい

## 実装機能

ユーザー

- 掲示板に x 月 y 日 場所: 〇〇 のように、服を見に行きたい日程と場所を投稿できる
- 掲示板を見て、投稿しているユーザーのプロフィールを modal で見れる。ユーザー詳細ページにも飛べる
- 気になったユーザーにメッセージを送れる

## ER 図

<img src="https://i.gyazo.com/61bb09a9566356e0a9556006cf2fb979.png">

## 起動
`git clone --recursive https://github.com/kaze0000/Go-With-Fashion.git`

`docker-compose build`

`docker-compose up`

`docker-compose exec api rails db:create`

`docker-compose exec api rails db:migrate`

`docker-compose exec api rails db:seed`

` docker-compose exec front npm i typescript`
