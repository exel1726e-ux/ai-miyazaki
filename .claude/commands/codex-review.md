---
description: Codex に変更内容をレビューさせる
---
`git diff HEAD` で変更を確認し、差分があれば
`codex exec --sandbox read-only "git diff HEAD をレビューして。日本語で、問題点と改善案を重要度順に簡潔に"`
を実行する。差分がなければ、直近に編集したファイルを対象にする。
結果を要約して、反映すべき指摘と見送る指摘に分けて報告する。
