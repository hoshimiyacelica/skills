# Skills

日本語 | [English](README.en.md)

このリポジトリでは、AI コーディングエージェントで利用できる再利用可能なスキルを公開しています。日本語の文章作成と添削、日本語と台湾華語の翻訳に使えるスキルを提供しています。Claude Fable 5 向けに要点を圧縮した Fable 版は、[`fable/`](fable/) フォルダにまとめています。

## 公開しているスキル

| スキル | 用途 |
| --- | --- |
| [`japanese-writing-style`](japanese-writing-style/SKILL.md) | 元の意味や引用部分の表記を保ちながら、自然で読みやすい日本語の文章を作成したり、添削したりするためのスキルです。 |
| [`japanese-writing-style-fable`](fable/japanese-writing-style-fable/SKILL.md) | Claude Fable 5 向けに要点を圧縮した、日本語の文章作成と添削のためのスキルです。 |
| [`ja-zhtw-translation`](ja-zhtw-translation/SKILL.md) | 日本語と台湾華語を、チャットや SNS の文脈とニュアンスに合わせて双方向に翻訳するためのスキルです。 |
| [`ja-zhtw-translation-fable`](fable/ja-zhtw-translation-fable/SKILL.md) | Claude Fable 5 向けに要点を圧縮した、日本語と台湾華語の翻訳のためのスキルです。 |

## インストール方法

Codex または Claude Code に、[hoshimiyacelica/skills](https://github.com/hoshimiyacelica/skills) から使いたいスキルをインストールするよう依頼してください。

```text
GitHub の hoshimiyacelica/skills から japanese-writing-style と ja-zhtw-translation をインストールしてください。
```

スキルを明示的に利用する場合は、プロンプトの中で `$japanese-writing-style` や `$ja-zhtw-translation` のように指定してください。スキルの自動選択に対応しているエージェントでは、文章作成や翻訳を依頼したときに、対応するスキルが自動で選択される場合があります。

## ライセンス

このリポジトリは、[MIT License](LICENSE) の条件に基づいて公開しています。
