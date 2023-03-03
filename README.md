# seichi-portal

Seichi Portalは、整地鯖の運営でこれまで使っていた Google Formsを一元化するためのアプリケーションです。このリポジトリでは、各リポジトリに共通の情報をまとめています。

## プロジェクトの目的

これまでギガンティック☆整地鯖の運営では、Google Formsを用いてユーザーからの要望等を管理してきました。しかし、フォームの種類が増えるにつれ管理が煩雑になってきたことから、内製化の機運が高まりました。

## 各リポジトリについて

|名称|説明|
|---|---|
|[フロントエンド](https://github.com/GiganticMinecraft/seichi-portal-frontend)|Node.jsを用いたSPAです。バックエンドやMicrosoftなどの外部APIと通信を行い、ユーザーに情報を視覚的に提供します。|
|[バックエンド](https://github.com/GiganticMinecraft/seichi-portal-backend)|Rustを用いたWebサーバーです。フロントエンドと通信を行い、必要なデータをDBに永続化することを担当します。|
|[API定義](https://github.com/GiganticMinecraft/seichi-api-schema)|フロントエンドとバックエンドの通信はREST APIであり、そのスキーマの定義を行っています。|

## プロジェクト俯瞰図

![image](./docs/overhead-view.drawio.svg)

## ライセンス

[Apache License 2.0](./LICENSE)
