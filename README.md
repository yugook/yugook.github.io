# yugook.github.io
利用規約・プライバシーポリシー公開用（GitHub Pages）

## 構成
- 開発者ページ: `developer/ja/index.html` と `developer/en/index.html`
- 入口ページ: `legal/index.html` と `legal/en/index.html`
- サポートページ: `<app>/support/<lang>/`
- 法務ページ: `legal/<app>/terms/<lang>/` と `legal/<app>/privacy/<lang>/`
- 共通スタイル: `legal/assets/legal.css`
- 更新通知用JSON: `legal/<app>/policy.json`

## 更新時のメモ
- 連絡先は `_data/legal.yml` の `contact_email` を更新する
- 更新日は `_data/legal.yml` の `last_updated.developer` / `last_updated.support` / `last_updated.terms` / `last_updated.privacy` を更新する
- 開発者ページの Zenn / GitHub / X / note / dev.to URL は `_data/legal.yml` の `developer_links` を更新する
- App Store URL は `_data/legal.yml` の `apps.<app>.app_store_url` に設定する

## アクセス方法
- 公開URL: `https://<username>.github.io/`（入口: `/legal/` と `/legal/en/`、開発者ページ: `/developer/ja/` と `/developer/en/`）
- 実際のURLは GitHub の Settings → Pages で確認
