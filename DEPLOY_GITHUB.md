# GTAJテストサイトを公開する（GitHub Pages）

公開リポジトリ： https://github.com/Oheavenus/gtaj-renewal

HTML全8ページ・CSS・JavaScriptは `main` に登録済みです。

## 初回のみ必要な設定

1. https://github.com/Oheavenus/gtaj-renewal/settings/pages を開く。
2. **Build and deployment** の **Source** で **Deploy from a branch** を選択。
3. **Branch** に `main`、フォルダに `/(root)` を指定。
4. **Save** を押す。

公開URL： https://oheavenus.github.io/gtaj-renewal/

公開後に `main` のHTML・CSS等を更新すると、Pagesの設定が有効である限り再デプロイされます。

現行 `https://gtaj.or.jp/` は変更されません。この試作は検索エンジン向けに `noindex` を指定していますが、URLを知っている方は閲覧できます。
