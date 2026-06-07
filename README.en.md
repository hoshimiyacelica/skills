# Skills

[日本語](README.md) | English

This repository provides reusable skills for AI coding agents.

## Available skill

| Skill | Purpose |
| --- | --- |
| [`japanese-writing-style`](japanese-writing-style/SKILL.md) | Write and edit clear, natural Japanese prose while preserving meaning and quoted material. |

## Installation

Clone or download this repository, then copy the skill directory you want to use into your agent's skill directory.

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

Invoke the skill explicitly with `$japanese-writing-style`. Agents that support automatic skill selection may also select it when creating or editing Japanese prose.

## License

This repository is available under the [MIT License](LICENSE).
