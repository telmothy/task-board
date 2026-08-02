# task-board プロジェクトについて

私的・研究用プロジェクト（教材ではない、通常のソフトウェア開発として扱う）です。

- 技術スタック: React + Vite（JavaScript）
- 開発サーバー起動: `npm run dev`
- Lint: `npm run lint`
- ビルド: `npm run build`

## Git運用ルール

- このプロジェクトはGitで管理し、GitHubにリモートリポジトリ（`origin` = https://github.com/telmothy/task-board.git）を持つ
- **コードを変更するたびに、コミットしてGitHubにプッシュすること**
  - 小さい変更でもまとめずに都度コミット・プッシュする
  - コミットメッセージは変更内容が分かるように簡潔に書く
- プッシュ前に `git status` / `git diff` で変更内容を確認する
- force push など破壊的な操作は行わない（必要な場合は必ずユーザーに確認する）
