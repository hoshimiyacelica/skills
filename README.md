# Skills

日本語 | [English](README.en.md)

AI コーディングエージェント向けの再利用可能な skill を公開するリポジトリです。

## 公開中の skill

| Skill | 用途 |
| --- | --- |
| [`japanese-writing-style`](japanese-writing-style/SKILL.md) | 元の意味や引用を保ちながら、自然で読みやすい日本語の文章を作成、添削します。 |

## インストール

このリポジトリをクローンまたはダウンロードし、使いたい skill のディレクトリをエージェントの skill ディレクトリへコピーします。

Codex:

```bash
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -R japanese-writing-style "${CODEX_HOME:-$HOME/.codex}/skills/"
```

Claude Code:

```bash
mkdir -p "$HOME/.claude/skills"
cp -R japanese-writing-style "$HOME/.claude/skills/"
```

`$japanese-writing-style` と指定すると、skill を明示的に呼び出せます。skill の自動選択に対応するエージェントでは、日本語の文章を作成、添削するときに自動で選択される場合があります。

## ライセンス

このリポジトリは [MIT License](LICENSE) のもとで公開しています。
