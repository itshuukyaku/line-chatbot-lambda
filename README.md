# chatbot

## 概要
このリポジトリは、LINEチャットボットをAWS Lambda上で動作させるためのプロジェクトです。

## 特徴
- LINE Messaging APIを使用
- AWS Lambdaでサーバーレスアーキテクチャを実現
- 簡単にデプロイ可能

## 必要なもの
- AWSアカウント
- LINE Developersアカウント
- Node.js

## セットアップ
1. リポジトリをクローンします。
    ```bash
    git clone https://github.com/yourusername/line-chatbot-lambda.git
    cd line-chatbot-lambda
    ```
2. 必要なパッケージをインストールします。
    ```bash
    npm install
    ```
3. 環境変数を設定します。
    ```bash
    cp .env.example .env
    # .envファイルを編集して必要な情報を入力します
    ```

## デプロイ
1. AWS CLIを使用してデプロイします。
    ```bash
    npm run deploy
    ```

## 使用方法
LINEアプリでチャットボットと対話することで、設定した応答を確認できます。

## ライセンス
このプロジェクトはMITライセンスの下で公開されています。

