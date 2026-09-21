# レシピの保存庫 デモレシピ集

App StoreスクリーンショットとApp Reviewで使用するための静的デモサイトです。

## ファイル
- index.html: デモレシピ一覧
- 6つの個別レシピHTML
- style.css
- images/: デモ用料理画像

## GitHub Pagesへの追加
既存の recipebox-site リポジトリへ、たとえば `demo/` フォルダを作成し、このZIPの中身をそのまま配置してください。
公開後は `.../demo/` が一覧ページ、`.../demo/chicken-tomato.html` 等が個別ページになります。

## RecipeBox検証
各個別ページには Schema.org Recipe JSON-LD、og:image、twitter:image、材料・作り方の通常HTMLを含めています。
