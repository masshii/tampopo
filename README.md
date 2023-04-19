# たんぽぽ書道教室

書道教室の先生と保護者をつなぐ連絡用webアプリ
![image](https://user-images.githubusercontent.com/106829132/232290769-d352beef-05cf-436d-b517-3e0861d79d33.png)

## 作成した目的

運営者（先生）から生徒の状況や、教室での活動内容を効率的に保護者と共有できるシステムが必要との要望があり開発を行った。

## サイト概要

書道教室が運営するwebアプリです。

ユーザーの管理や生徒情報の管理ができます。

書道教室からのお知らせ新規投稿作成時に管理者からユーザー（保護者）にメール送信でお知らせできます。

お知らせの投稿に既読機能、いいね機能、コメント機能を搭載しユーザー参加型にしました。

## たんぽぽ書道教室URL

https://tampopo-kyoshitsu.com

ご登録はこちらより会員登録後、ログインしてください。

レスポンシブ対応していますのでスマートフォンからでもご利用いただけます。

## 他のリポジトリ

ローカルの開発環境、本番環境（Xserver）

## 機能一覧

・ ユーザー側機能

　◦ 新規登録、ログイン、ログアウト機能
 
　◦ メール認証機能
 
　◦ アバター登録、表示機能
 
　◦ アカウント編集機能
 
　◦ コメント機能
 
　◦ 投稿にいいねを付与、削除機能
 
　◦ 既読機能
 
　◦ お問い合わせ機能 


・ 管理者側機能

　◦ 各ユーザーのアカウント編集、削除機能
 
　◦ お知らせ投稿、編集、削除機能
 
　◦ 生徒登録、編集、削除機能
 
 
 ・その他機能
 
 　◦ページネーション機能
 
 　◦Gate、Policy機能
 
 　◦Notification機能
 
## 使用技術(実行環境)

・ 開発環境 : Laravel Sail （Doker使用）

・ 言語 : PHP

・ フレームワーク : Laravel Framework 10.5.1

・ データベース : MYSQL 8.0.32

## テーブル設計

![image](https://user-images.githubusercontent.com/106829132/232238636-e5a76c0b-7114-4272-8ffe-558d0139e9e4.png)

## ER図

![image](https://user-images.githubusercontent.com/106829132/232240834-7f0b3966-f635-4b44-a431-3e0f8566e1c1.png)

## 環境構築

最初にcomposer installコマンドを実行してライブラリをインストールしてください。

データベース作成後、php artisan migrateコマンドを実行してテーブルを作成してください。

.envファイルは、.env.exampleを参考に、別途ご用意ください。

## アカウントの種類

管理者、一般ユーザー、テストユーザー
