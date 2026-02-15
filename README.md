# X Trend Brief

インディーズ/個人開発ゲームの発掘と、X（旧Twitter）への自動投稿を行うボットです。

## 機能

- Steam / itch.io からインディーズゲームを自動収集
- X トレンドの解説投稿（1日1本）
- AI（Gemini）によるコンテンツ生成
- 1日最大6本の自動投稿

## 技術スタック

- Bun + TypeScript + Express + PostgreSQL
- Google Gemini API / X API v2

## セットアップ

1. `bun install`
2. `.env.example` をコピーして `.env` を作成
3. `DATABASE_URL` / `X_API_BEARER_TOKEN` / `GEMINI_API_KEY` を設定
4. `bun run local:setup` で初期セットアップ
5. `bun start` で起動

## ドキュメント

- [利用規約](TERMS.md)
- [プライバシーポリシー](PRIVACY.md)

## ライセンス

MIT
