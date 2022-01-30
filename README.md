# Sample Apify

Apifyを試してみたサンプルコードです

ref https://sdk.apify.com/docs/guides/motivation

## 環境

* node: 16.6.2
    * https://github.com/apify/apify-js#local-stand-alone-usage にあるように 15.10 以降を指定してください
* apify: 2.2.1
* playwright: 1.8.1

## 実行

```
$ npm install
$ npm run start
```

## その他

* `apify_storage`以下のディレクトリは、apify実行時に自動生成しますので、初回起動時は存在していなくても実行可能です。
* [apify-cli](https://github.com/apify/apify-cli) は、Apify Platformを使う場合には非常に有力なツールのようです。ローカルでApifyを実行させる上では必須ではありません。

