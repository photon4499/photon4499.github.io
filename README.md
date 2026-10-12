# 今日の一問 — TikTok アプリ用サイト

[short-movie_remotion](https://github.com/photon4499/short-movie_remotion) の TikTok 開発者アプリ登録に使う GitHub Pages サイトです。

## 公開手順

1. リポジトリ名を `photon4499.github.io` に変更（Settings → General → Repository name）
2. Settings → Pages → Source を「Deploy from a branch」、Branch を `main` / `/ (root)` にして Save
3. 数分後に https://photon4499.github.io/ が表示されることを確認

## TikTok for Developers に登録する URL

| 項目 | URL |
| --- | --- |
| Web サイト | https://photon4499.github.io/ |
| 利用規約 | https://photon4499.github.io/terms.html |
| プライバシーポリシー | https://photon4499.github.io/privacy.html |
| Redirect URI | https://photon4499.github.io/callback/ |

Redirect URI は `npm run tiktok:auth` の `TIKTOK_REDIRECT_URI` と末尾の `/` まで完全に一致させてください。
