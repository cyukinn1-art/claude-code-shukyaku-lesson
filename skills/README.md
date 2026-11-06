# 個人用Skillの保管場所

このフォルダには、個人用Skillのコピーを置いています。

クラウドのClaude Codeは、セッションが終わると個人フォルダ（`~/.claude/skills/`）が消えます。そのため、ここにコピーを残しています。
このフォルダはClaude Codeが自動で読み込む場所ではないので、使う前に次のコマンドで個人フォルダへコピーしてください。

## 自分のPCで使う場合（Mac／Linux）

```bash
mkdir -p ~/.claude/skills && cp -r skills/design-doc ~/.claude/skills/
```

コピーした後に新しいClaude Codeセッションを始めると、`design-doc` Skillが使えるようになります。

## 中身

- `design-doc/SKILL.md`：Skillの入口。いつ使うか、何を必ず守るか
- `design-doc/references/base-rules.md`：設計書作成ルールの本体（基本ルール）
- `design-doc/preferences.md`：個人の好み。ここを書き換えると、Claudeの設計書の作り方が変わる
