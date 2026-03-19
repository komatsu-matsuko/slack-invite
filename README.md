# Slack 参加案内

- **トップページ (Slackに参加してね!)**: `index.html`
- **参加手順マニュアル**: `slack-参加手順.html`

## URL で公開する方法（GitHub Pages）

1. [GitHub](https://github.com) で新しいリポジトリを作成（例: `slack-invite`）。**README や .gitignore は追加しない**（空のリポジトリ）。
2. ターミナルでこのフォルダ（招待）に移動し、以下を実行:

```bash
cd "/Users/komatsu/招待"
git init
git add index.html slack-参加手順.html .nojekyll
git commit -m "Slack参加案内ページ"
git branch -M main
git remote add origin https://github.com/【あなたのユーザー名】/slack-invite.git
git push -u origin main
```

3. GitHub のリポジトリ → **Settings** → **Pages** → **Source**: "Deploy from a branch" → **Branch**: `main`、**Folder**: `/ (root)` → **Save**。
4. 1〜2分後、次の URL で公開されます:  
   **https://【あなたのユーザー名】.github.io/slack-invite/**

このURLを新人に送れば、「Slackに参加してね！」のページが開きます。
