# Skills

[日本語](README.md) | English

This repository provides reusable skills for AI coding agents. It currently includes skills for Japanese prose and Japanese/Taiwan Mandarin translation.

## Available skills

| Skill | Purpose |
| --- | --- |
| [`japanese-writing-style`](japanese-writing-style/SKILL.md) | Write and edit clear, natural Japanese prose while preserving meaning and quoted material. |
| [`japanese-writing-style-fable`](fable/japanese-writing-style-fable/SKILL.md) | A concise version of the Japanese prose writing and editing skill. |
| [`ja-zhtw-translation`](ja-zhtw-translation/SKILL.md) | Translate between Japanese and Taiwan Mandarin with attention to chat, social media context, and nuance. |
| [`ja-zhtw-translation-fable`](fable/ja-zhtw-translation-fable/SKILL.md) | A concise version of the Japanese/Taiwan Mandarin translation skill. |

## Installation

Ask Codex or Claude Code to install the skills you want from [hoshimiyacelica/skills](https://github.com/hoshimiyacelica/skills).

```text
Install japanese-writing-style and ja-zhtw-translation from the hoshimiyacelica/skills repository on GitHub.
```

Invoke a skill explicitly with `$japanese-writing-style` or `$ja-zhtw-translation`. Agents that support automatic skill selection may also select the matching skill when writing, editing, or translating text.

## License

This repository is available under the [MIT License](LICENSE).
