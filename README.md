# GTAJ サイトリニューアル — Visual renewal

現行 https://gtaj.or.jp/index.html の公開情報を引き継ぎ、ビジュアル面を更新した静的テストサイトです。

## 構成

- `index.html` トップ
- `concept.html` 設立趣旨・沿革
- `company.html` 組織概要
- `recruit.html` 役員紹介
- `service.html` 事業概要
- `newpage2.html` 食文化観光パートナー
- `newpage1.html` 特別寄稿
- `privacy.html` プライバシーポリシー
- `style.css` 共通スタイル
- `script.js` モバイルナビ

## 方針

* 新しい受託メニューや架空の実績・記事は掲載しません。
* 現行サイトで実際に使われている写真（gtaj.or.jp の画像URL）を暫定的に参照します。**画像の保存・リポジトリへの同梱はしていません。**
* GTAJの `gtaj_topimage.gif` は元サイトのメインビジュアルですが、構成全体を未確認のため今回のヘッダへの直接流用は見送っています。元画像は https://gtaj.or.jp/gtaj_topimage.gif 。
* 名前・住所・役職・金額などは現行サイトの記載を移植しており、更新確認はしていません。
* 本部住所の `東京都静岡県静岡県...` は元の記載のまま残し、確認を促しています。
* 外部写真への直接リンクは現行サイトに依存します。長期運用時は利用許諾と元ファイルを確認し、ローカル配置へ切り替えてください。
* 試作なので `noindex, nofollow` を指定。公開URLへのアクセスは可能です。

## 公開

公開GitHubリポジトリの `main` ブランチにこれらのファイルを置き、GitHub Settings > Pages > Deploy from a branch > `main` / `(root)` を有効にします。

## 留意

これはデザインプレビュー用です。現行公開情報と照合した後で正式公開してください。