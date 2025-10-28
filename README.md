# 申請フォーム起動プラットフォーム（静的版）

このフォルダ一式を GitHub Pages で公開すると、スマホから 1/2/3 またはボタンで
「休暇届・残業届・購入予定品」の各 Google フォームを開けるポータルになります。

## 使い方（超簡単）
1. GitHub で新しいリポジトリを作成（例: `chiyoda-forms`）。
2. この ZIP を解凍し、中身（`index.html` など）をそのリポジトリにアップロード。
3. リポジトリの `Settings → Pages` で Source を `Deploy from a branch`、Branch を `main`、Folder を `/ (root)` に設定 → Save。
4. 表示された URL（例: `https://ユーザー名.github.io/chiyoda-forms/`）を職員へ共有。
5. 職員はスマホで開き、「ホーム画面に追加」するとアプリのように使えます。

## カスタマイズ
- タイトルや説明文は `index.html` の `<header>` 部分を編集してください。
- リンク先 URL は `index.html` の `LINKS` 定数を変更します。

## 注意
- このページ自体は公開サイトです。閲覧制限をしたい場合は Google フォーム側でドメイン制限等をご設定ください。
