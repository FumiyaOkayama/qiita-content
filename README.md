# Qiita-content

qiitaの記事を同期・執筆・投稿するためのリポジトリ

## 使い方

### 環境設定

https://github.com/increments/qiita-cli 参照。

### 新規記事の作成

```bash
npx qiita new 記事のファイルのベース名
```

### プレビュー画面の表示

```bash
npx qiita preview
```

http:localhost:8888 でプレビュー画面が表示されます。

### Qiitaへの投稿

masterブランチにpushすると、自動的にQiitaへ投稿されます。

### 投稿記事の同期

```bash
npx qiita pull
```
