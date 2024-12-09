# 📂 Mintlify-Docs

## *AI連携を可能にするウェブ編集システム"Mintlify"*

###### このリポジトリはMintlifyの紹介を目的としてます  
 
### ⚙️このリポジトリの使い方  
 

#### 要件（手順）

`1` このレポジトリをローカルにクローンします。(詳細省略)

`2` ツールをデバイスにインストールする必要があります。

```
npm i -g mintlify
```
必要に応じて
```
npm i @mintlify/cli
```


`3` Mintlifyにユーザー登録する必要があります。
> パーソナルユースでも*登録の際はあくまでも（個人）ですが、GitHubに base Repository を設置するときはGitHubの（会社/団体）と（個人）のアカウントが両方必要です*

>> 詳細は下記（オフィシャルサイトのドキュメント）を確認して行ってください

`4` 編集を開始します。

ローカル環境（ワーキングディレクトリ）で次のコマンドにより
```
mintlify dev --port 3333
``` 
インスタンス（サーバー）を立ち上げプレビューします。


`5` 編集画面（ダッシュボード）へは右上の**Dashboard**ボタンからアクセスします。

👍 以上でドキュメント（コンテンツ）を新規作成しWEB公開できます。  
😊 是非お試しください。

なお、このリポジトリには公開コンテンツを./mintlify-docs内に格納しています。
サイト構成やファイル配置の参考にしてください。



公開URL：https://watanabe3ti.mintlify.app/

## 🚀

---

> 以下はオフィシャルサイトのコンテンツと同じです。


## 🌐 Official Site (Mintlify Starter Kit）

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

* Guide pages

* Navigation

* Customizations

* API Reference pages

* Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard.

#### Troubleshooting

* Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.

* Page loads as a 404 - Make sure you are running in a folder with `mint.jso`





> ローカル環境では \`\`\`mintlify dev --port 3333\`\`\` でインスタンス（サーバー）を立ち上げてプレビューします