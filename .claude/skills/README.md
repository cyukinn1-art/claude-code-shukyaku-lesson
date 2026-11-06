# このリポジトリのSkill

このフォルダ（`.claude/skills/`）に置いたSkillは、このリポジトリでClaude Codeを使うと自動で読み込まれます。クラウドのセッションでも、自分のPCでも同じです。コピーなどの準備はいりません。

## design-doc（設計書作成Skill）

新しいツールを実装する前に、Claude Codeが実装に使える設計書を作ります。

- `design-doc/SKILL.md`：Skillの入口。いつ使うか、何を必ず守るか
- `design-doc/references/base-rules.md`：設計書作成ルールの本体（基本ルール）
- `design-doc/preferences.md`：個人の好み。ここを書き換えると、Claudeの設計書の作り方が変わる

## 他のプロジェクトでも使いたい場合

自分のPCの個人用フォルダにコピーすると、そのPCのすべてのプロジェクトで使えます。

```bash
mkdir -p ~/.claude/skills && cp -r .claude/skills/design-doc ~/.claude/skills/
```

> このリポジトリの中で作業するときに、個人用フォルダにも同じ名前のSkillがあると、2つ表示されることがあります。その場合はどちらか一方を消してください。
