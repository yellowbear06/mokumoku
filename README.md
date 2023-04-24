# README

## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください

【実装方針】

ログイン後、HobbyとProfileを登録できる
他のユーザーのHobbyとProfileを閲覧できる。
他のユーザーをフォローできるし、フォロー解除することもできる。

【注意点】

usersテーブルに"profile"・"hobby"カラムを追加する。
フォロー・アンフォローするボタンは"フォローする"・"フォローを外す"とする。
