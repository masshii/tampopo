# たんぽぽ書道教室

書道教室の先生と保護者を繋ぐ連絡用webアプリ
![image](https://user-images.githubusercontent.com/106829132/232290303-3cba2764-6c5c-4425-a67a-8b0232ffb519.png)

## 作成した目的

運営者（先生）から生徒の状況や、教室での活動内容を効率的に保護者と共有できるシステムが必要との要望があり開発を行った。

## たんぽぽ書道教室URL

https://tampopo-kyoshitsu.com

## 他のリポジトリ

Xserver

## 機能一覧

・ ユーザー側

　◦ 新規登録、ログイン機能、ログアウト機能
 
　◦ メール認証機能
 
　◦ アバター機能
 
　◦ アカウント編集機能
 
　◦ コメント機能
 
　◦ いいね機能
 
　◦ 既読機能
 
　◦ お問い合わせ機能 


・ 管理者側

　◦ アカウント編集機能、削除機能
 
　◦ お知らせ投稿、編集、削除機能
 
　◦ 生徒登録、編集、削除機能
 
 
 ・ ページネーション機能
 
 ・ Gate、Policy機能
 
 ・ Notification機能
 
## 使用技術(実行環境)

・ OS : Docker/Docker-compose

・ 言語 : PHP

・ フレームワーク : Laravel Framework 10.5.1

・ データベース : MYSQL 8.0.32

## テーブル設計

![image](https://user-images.githubusercontent.com/106829132/232238636-e5a76c0b-7114-4272-8ffe-558d0139e9e4.png)

## ER図

![image](https://user-images.githubusercontent.com/106829132/232240834-7f0b3966-f635-4b44-a431-3e0f8566e1c1.png)

## 環境構築

ライブラリインストールの為にcomposer installコマンドを実行してください。

データベースの取得はphp artisan migrateコマンドを実行してください。

.envファイルは別途ご用意ください。

## アカウントの種類

管理者、一般ユーザー、テストユーザー
