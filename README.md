# Koppen Sleepy Profile Link Page

このプロジェクトは、DJ・声優・アイドルのプロフィールリンクページです。
GitHub Pages で簡単に公開できるように構成されています。

## 🚀 GitHub Pages での公開手順

1. **リポジトリの作成**: GitHub で新しいリポジトリを作成し、このプロジェクトのファイルをすべてアップロード（push）します。
2. **画像の設定**: `src` フォルダの中に、自分のプロフィール画像を `profile.png` という名前で保存してください。
3. **GitHub Pages の有効化**:
   - リポジトリの **Settings** > **Pages** を開きます。
   - **Build and deployment** > **Source** を `Deploy from a branch` に設定。
   - **Branch** を `main` (または `master`) に設定して **Save** を押します。
4. **完了**: 数分後、`https://<あなたのユーザー名>.github.io/<リポジトリ名>/` で公開されます。

## 📸 プロフィール画像の変更方法

GitHub Pages は静的なホスティングサービスのため、ブラウザ上の画面から画像をアップロードして保存することはできません。

画像を変えたい場合は、**GitHub 上の `src/profile.png` ファイルを新しい画像で上書きアップロード**してください。反映には数分かかる場合があります。

## 🛠 ローカルでの開発

ローカル環境でサーバー機能を試したい場合は、以下のコマンドを使用します。

```bash
npm install
npm run dev
```

管理者ページ（`/admin`）を使用して画像をアップロードする機能は、ローカル実行時または Node.js が動作するサーバー（Heroku, Render 等）でのみ動作します。
