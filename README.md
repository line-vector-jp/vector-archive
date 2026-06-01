# LINE公式アカウント攻略 (Archive)

[vector.jp.net](https://vector.jp.net/) のブログ記事を、GitHub Pages 用に静的サイトとしてアーカイブしたものです。

## 内容

- 記事数: **49 件**（#001〜#049）
- 固定ページ: **5 件**（オススメ理由 / まずは開設 / Lステップについて / Lステップ vs Liny / ふさわしいお客様）
- 埋め込み: YouTube 自己紹介動画、LINE 友だち追加ボタン＋QRコード、Instagram（@line_vector）
- 画像: 全 記事内画像をローカル化
- 構成:
  - `index.html` … ホーム（メニュー、YouTube/LINE/Instagram 埋め込み、記事一覧）
  - `articles/<post_id>.html` … 個別記事ページ
  - `pages/<slug>.html` … 固定ページ（recommend / start / lstep / lstep-vs-liny / customer）
  - `assets/styles.css` … 共通スタイル
  - `assets/images/` … 全画像
  - `sitemap.xml`, `.nojekyll`

## GitHub Pages での公開方法

1. このフォルダ（`site/`）の中身を、公開用リポジトリのルートにそのままコミットします。
2. リポジトリの **Settings → Pages** を開き、Source を「Deploy from a branch」、Branch を `main` (root) に設定。
3. 数十秒待つと `https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

`.nojekyll` を含めているため、Jekyll の処理は走らずファイル名そのままで配信されます。

## ライセンス / 出典

本サイトの記事本文・画像の著作権は [vector.jp.net](https://vector.jp.net/) の運営者に帰属します。本リポジトリはアーカイブ目的の再構築であり、商用利用や転載の許可は別途確認してください。
