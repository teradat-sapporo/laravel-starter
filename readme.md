# Laravel Starter

## 目標
Laravelの開発環境をDockerを用いて最小限の構成で立ち上げる。

## やること
1.  laravel-starterに移動し、srcフォルダを作成する。
1.  以下のコマンドを順に実行していく
1.  docker-compose build
1.  docker-compose up -d
1.  docker-compose exec web composer create-project laravel/laraevl ./
1.  プロジェクトが生成できたら、以下のコマンドでサーバを立ち上げる
1.  docker-compose exec web php artisan serve --host 0.0.0.0
1.  ブラウザで「http://localhost:8000」に接続する
1.  Laravelのウェルカムページが出たら成功