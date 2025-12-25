# React Router サンプルアプリ

React Router v6 を使った基本的なルーティングのデモアプリです。

## 技術スタック

- React 18
- TypeScript
- react-router-dom v6

## 機能

シンプルな2ページ構成のSPAです。

| パス | ページ |
|------|--------|
| `/` | Home Page |
| `/about` | About Page |

## セットアップ

```bash
# 依存関係のインストール
npm install

# 開発サーバー起動
npm start
```

http://localhost:3000 でアプリが開きます。

## プロジェクト構成

```
src/
├── App.tsx       # ルーティング設定とページコンポーネント
├── index.tsx     # エントリーポイント
└── ...
```

## 利用可能なスクリプト

| コマンド | 説明 |
|----------|------|
| `npm start` | 開発サーバー起動 |
| `npm test` | テスト実行 |
| `npm run build` | 本番用ビルド |
