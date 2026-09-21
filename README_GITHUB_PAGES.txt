RecipeBox 公開用サイト（GitHub Pages向け）

含まれるファイル
- index.html      : トップページ
- privacy.html    : プライバシーポリシー
- support.html    : サポートページ
- style.css       : 共通スタイル

公開前に必ず置換する箇所
1. [開発者名]
2. [問い合わせ用メールアドレス]

おすすめの公開方法（GitHub Pages）
1. GitHubで公開リポジトリを新規作成
   例: recipebox-site
2. このフォルダ内の4ファイルをリポジトリ直下へアップロード
3. GitHubの Settings → Pages を開く
4. Build and deployment で
   Source: Deploy from a branch
   Branch: main / root
   を指定して保存
5. 数分後に公開URLが発行されます

想定URL例
https://あなたのGitHubユーザー名.github.io/recipebox-site/

App Store Connectでは
- Privacy Policy URL:
  https://.../privacy.html
- Support URL:
  https://.../support.html
を使用できます。

注意
- RecipeBoxアプリ本体のSwiftソースコードをこの公開リポジトリへ置く必要はありません。
- GitHub Pages用リポジトリには、この案内サイトのファイルだけを置けば十分です。
