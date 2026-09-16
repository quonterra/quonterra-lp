# quonterra-lp

QUONTERRA のランディングページ（静的サイト）。

- `public/index.html` — LP 本体
- `public/assets/` — 画像素材

Vercel プロジェクト `quonterra-lp`（Framework Preset: Other）が `public/` をそのまま配信します。ビルド工程はありません。

ローカル確認:

```bash
python3 -m http.server 4173 -d public
```
