# Handbookを編集する

## 1. ローカル環境を起動
```
docsify serve ./docs/
```

## 2. ローカル環境にアクセス
http://localhost:3000/ にアクセスする。

## 3. ローカル環境で編集する
1. masterブランチの内容を取り込む
    ```
    git branch master
    git pull origin master
    ```
2. ブランチを作成する。*にはissueのIDを設定する
    ```
    git checkout -b issues/*
    ```
3. 各ファイルを修正する
4. 修正したファイルをコミットする
    ```
    git add [対象ファイル名]
    git commit -m "issueの番号を含めて修正内容を記載する"
    ```
5. 修正したブランチをプッシュする
    ```
    git push origin [branch name]
    ```
6. Pull Requestをマージする
