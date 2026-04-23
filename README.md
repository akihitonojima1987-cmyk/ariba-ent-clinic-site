# 岩佐耳鼻咽喉科 ウェブサイト

静的HTMLによる岩佐耳鼻咽喉科（東京都中央区京橋・宝町駅徒歩30秒）のウェブサイトです。

## ページ構成

- `index.html` — トップページ
- `clinic.html` — クリニック紹介
- `staff.html` — スタッフ紹介
- `fees.html` — 費用について
- `notices.html` — 書面掲示について
- `faq.html` — よくある質問
- `recruit.html` — 求人情報

## デプロイ

Cloudflare Pages に GitHub 連携でデプロイしています。`main` ブランチへの push で自動デプロイされます。

- Framework preset: **None**
- Build command: （なし）
- Build output directory: `/`

## ローカルプレビュー

```bash
# Python が入っていれば
python -m http.server 8000
# → http://localhost:8000 でブラウザ表示
```
