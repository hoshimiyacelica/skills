# Skills

日本語 | [English](README.en.md)

このリポジトリでは、AI コーディングエージェントで利用できる再利用可能なスキルを公開しています。現在は、日本語の文章を自然で読みやすく整えるための `japanese-writing-style` を提供しています。

## 公開しているスキル

| スキル | 用途 |
| --- | --- |
| [`japanese-writing-style`](japanese-writing-style/SKILL.md) | 元の意味や引用部分の表記を保ちながら、自然で読みやすい日本語の文章を作成したり、添削したりするためのスキルです。 |

## インストール方法

このリポジトリをクローンまたはダウンロードしたあと、利用するスキルのディレクトリを、使用するエージェントのスキルディレクトリへコピーしてください。

### Codex

```bash
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -R japanese-writing-style "${CODEX_HOME:-$HOME/.codex}/skills/"
```

### Claude Code

```bash
mkdir -p "$HOME/.claude/skills"
cp -R japanese-writing-style "$HOME/.claude/skills/"
```

スキルを明示的に利用する場合は、プロンプトの中で `$japanese-writing-style` と指定してください。スキルの自動選択に対応しているエージェントでは、日本語の文章を作成したり、添削したりするときに、このスキルが自動で選択される場合があります。

## ライセンス

このリポジトリは、[MIT License](LICENSE) の条件に基づいて公開しています。
