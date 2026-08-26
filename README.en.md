# Skills

[日本語](README.md) | English

This repository provides reusable skills for AI coding agents. It currently includes skills for Japanese prose and Japanese/Taiwan Mandarin translation.

## Available skills

| Skill | Purpose |
| --- | --- |
| [`japanese-writing-style`](japanese-writing-style/SKILL.md) | Write and edit clear, natural Japanese prose while preserving meaning and quoted material. |
| [`ja-zhtw-translation`](ja-zhtw-translation/SKILL.md) | Translate between Japanese and Taiwan Mandarin with attention to chat, social media context, and nuance. |

## Installation

### As a Claude Code plugin

This repository doubles as a plugin marketplace. Run the following in Claude Code to install both skills at once.

```text
/plugin marketplace add hoshimiyacelica/skills
/plugin install ja-skills@hoshimiyacelica-skills
```

If the install summary reports `Run /reload-plugins to activate.`, run that command as well. Pull later updates with `/plugin marketplace update hoshimiyacelica-skills`.

### By asking an agent

For agents without plugin support, such as Codex, ask directly.

```text
Install japanese-writing-style and ja-zhtw-translation from the hoshimiyacelica/skills repository on GitHub.
```

Invoke a skill explicitly with `$japanese-writing-style` or `$ja-zhtw-translation`. Agents that support automatic skill selection may also select the matching skill when writing, editing, or translating text.

## License

This repository is available under the [MIT License](LICENSE).
