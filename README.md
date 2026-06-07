# Skills

日本語 | [English](README.en.md)

このリポジトリでは、AI コーディングエージェントで利用できる再利用可能なスキルを公開しています。現在は、日本語の文章を自然で読みやすく整えるための `japanese-writing-style` を提供しています。

## 公開しているスキル

| スキル | 用途 |
| --- | --- |
| [`japanese-writing-style`](japanese-writing-style/SKILL.md) | 元の意味や引用部分の表記を保ちながら、自然で読みやすい日本語の文章を作成したり、添削したりするためのスキルです。 |

## インストール方法

Codex または Claude Code に、[hoshimiyacelica/skills](https://github.com/hoshimiyacelica/skills) からスキルをインストールするよう依頼してください。

```text
GitHub の hoshimiyacelica/skills から japanese-writing-style をインストールしてください。
```

スキルを明示的に利用する場合は、プロンプトの中で `$japanese-writing-style` と指定してください。スキルの自動選択に対応しているエージェントでは、日本語の文章を作成したり、添削したりするときに、このスキルが自動で選択される場合があります。

## ライセンス

このリポジトリは、[MIT License](LICENSE) の条件に基づいて公開しています。
