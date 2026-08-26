# Skills

日本語 | [English](README.en.md)

このリポジトリでは、AI コーディングエージェントで利用できる再利用可能なスキルを公開しています。日本語の文章作成と添削、日本語と台湾華語の翻訳に使えるスキルを提供しています。

## 公開しているスキル

| スキル | 用途 |
| --- | --- |
| [`japanese-writing-style`](japanese-writing-style/SKILL.md) | 元の意味や引用部分の表記を保ちながら、自然で読みやすい日本語の文章を作成したり、添削したりするためのスキルです。 |
| [`ja-zhtw-translation`](ja-zhtw-translation/SKILL.md) | 日本語と台湾華語を、チャットや SNS の文脈とニュアンスに合わせて双方向に翻訳するためのスキルです。 |

## インストール方法

### Claude Code のプラグインとして入れる

このリポジトリはプラグインマーケットプレイスを兼ねています。Claude Code で次を実行すると、両方のスキルがまとめて入ります。

```text
/plugin marketplace add hoshimiyacelica/skills
/plugin install ja-skills@hoshimiyacelica-skills
```

インストール後の要約に `Run /reload-plugins to activate.` と出たときは、そのコマンドも実行してください。更新は `/plugin marketplace update hoshimiyacelica-skills` で取り込めます。

### エージェントに依頼して入れる

Codex など、プラグインに対応していないエージェントには、次のように依頼してください。

```text
GitHub の hoshimiyacelica/skills から japanese-writing-style と ja-zhtw-translation をインストールしてください。
```

スキルを明示的に利用する場合は、プロンプトの中で `$japanese-writing-style` や `$ja-zhtw-translation` のように指定してください。スキルの自動選択に対応しているエージェントでは、文章作成や翻訳を依頼したときに、対応するスキルが自動で選択される場合があります。

## ライセンス

このリポジトリは、[MIT License](LICENSE) の条件に基づいて公開しています。
