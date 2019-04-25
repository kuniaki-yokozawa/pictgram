# README

#pictgramの説明
* 写真を撮影・シェアできるサービス
* 写真によるコミュニケーション
* 友達と絡むのが大変そう、と思っている方でも十分楽しめる

###Herokuへログイン
* $ heroku login
* heroku: Enter your login credentials
* Email: example@example.com
* Password: ********
* Logged in as example@example.com

###Gitの準備
* $ git init

* git add .
* git commit -m "first commit"
* git remote add origin gitURL
* git push -u origin master

###HerokuへPushする
* $ heroku create
* $ git push heroku master
* $ heroku run rails db:migrate

###本稼働確認
* $ heroku open

* Ruby version
ruby '2.4.1'
* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
