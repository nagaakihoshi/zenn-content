# Zenn Content

このリポジトリは [Zenn](https://zenn.dev) の記事や本を管理するためのリポジトリです。

## セットアップ

Zenn CLI をインストールして使用可能な状態にします。

```bash
# 最新版の zenn-cli をインストール
npm install zenn-cli@latest
```

## 使い方

### 初期化
リポジトリを Zenn 用に初期化します（初回のみ）。
```bash
npx zenn init
```

### プレビュー
ローカルで記事や本をプレビューします。
```bash
npx zenn preview
```
ブラウザで `http://localhost:8000` を開くと内容を確認できます。

### 記事の作成
新しい記事を作成します。
```bash
npx zenn new:article
```
`articles` ディレクトリに新しいMarkdownファイルが生成されます。

### 本の作成
新しい本を作成します。
```bash
npx zenn new:book
```
`books` ディレクトリに新しいディレクトリが生成されます。

## リンク
- [📘 Zenn CLI ガイド](https://zenn.dev/zenn/articles/zenn-cli-guide)
- [📝 Zenn 公式サイト](https://zenn.dev)
