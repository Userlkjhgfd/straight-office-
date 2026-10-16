# Starlight Office

ブラウザ内保存型のアイドル事務所ガチャ・ライブ育成アプリ試作版です。

## GitHub Pages で公開する手順

1. GitHubで新しいリポジトリを作成します（例: `starlight-office`）。
2. このフォルダ内の `index.html` と `README.md` をリポジトリのルートにアップロードします。
3. リポジトリの **Settings → Pages** を開きます。
4. **Build and deployment** の Source を **Deploy from a branch** にし、Branch は `main`、フォルダは `/(root)` を選び、Saveします。
5. Pagesの公開処理が終わったら、同じ設定画面の **Visit site** から開きます。

GitHub Pages は静的HTML/CSS/JavaScriptを公開できます。公開サイトはインターネット上で見られるため、個人情報や秘密のデータをHTMLに含めないでください。

## 保存について

ゲームデータはブラウザの localStorage に保存されます。GitHubへのコード更新はセーブデータを同期しません。ブラウザのデータ消去や端末変更に備え、アプリ内の「保存・設定」からバックアップを書き出してください。

## 注意

これは試作版です。ガチャ対象には登録済みアイドルが使われます。サーバー同期やアカウント機能はありません。
