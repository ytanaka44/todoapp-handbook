# 実行ログ

## version
- ```node -v```: v18.16.0
- ```npm -v```: 9.5.1





## docsifyのインストール＆実行
```
npm i docsify-cli -g
npx docsify init ./docs
docsify serve ./docs
```
※エラーが出る場合はsudo権限で実行する。

http://localhost:3000 にアクセスするとブラウザでドキュメントを確認できる。


## textlintをインストール
```
npm install textlint --save-dev
```

## smarthrのプリセットをインストール
```
npm install textlint-rule-preset-smarthr
```
## textlintrc.jsonの作成
```
npx textlint init
```
