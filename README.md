# for-her-videos

このリポジトリは、彼女専用の小さな静的サイトです。

## セットアップ手順
1. このリポジトリに `index.html`, `css/styles.css`, 各動画ページをアップロードします。
2. 各動画ページの `REPLACE_ID` を、あなたが限定公開でアップロードしたYouTube動画のIDに置き換えます。
   - 例: `https://www.youtube.com/watch?v=abc123` → ID は `abc123`
   - 埋め込み用URL: `https://www.youtube.com/embed/abc123`
3. GitHub 上で Settings → Pages に移動し、Source を `main`、Folder を `/root` にして Save を押す
4. 数分待つと `https://ユーザー名.github.io/リポジトリ名/` で公開されます。

## 補足
- 追加のカスタマイズ（色やフォント）は `css/styles.css` を編集
- 画像やBGMを使いたい場合は、`assets/` フォルダを作って追加可能
