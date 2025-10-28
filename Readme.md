# GitHub Pages公開手順

## 新しいリポジトリを作る（または既存のを使う）

## GitHubにログイン
右上の「＋」 → New repository

## リポジトリ名の決定
リポジトリ名：`ユーザー名.github.io`
例）haruyama123.github.io

## 公開（Public）でOK
「Create repository」押す
※このリポジトリ名の形式が「ユーザーサイト」の条件。

## ローカルにクローン

```
git clone https://github.com/ユーザー名/ユーザー名.github.io.git
cd ユーザー名.github.io
```

## index.htmlの作成
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Hello</title>
  </head>
  <body>
    <h1>Hello World</h1>
    <p>GitHub Pages テストページです。</p>
  </body>
</html>
```

コミット＆プッシュ

## GitHub Pagesの有効化

GitHub上のリポジトリページへ
右上の「Settings」タブへ
左メニューで「Pages」をクリック

「Branch」欄で　main（またはmaster）ブランチを選択 → 「Save」

数十秒待つとURLが出る　https://ユーザー名.github.io/

 複数リポジトリで複数ページ作成も可能

 

