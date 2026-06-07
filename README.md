# Skills

Reusable skills for AI coding agents.

## Available skill

| Skill | Purpose |
| --- | --- |
| [`japanese-writing-style`](japanese-writing-style/SKILL.md) | Write and edit clear, natural Japanese prose while preserving meaning and source material. |

## Installation

Clone or download this repository, then copy the skill directory into the
skills directory used by your agent.

For Codex:

```bash
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -R japanese-writing-style "${CODEX_HOME:-$HOME/.codex}/skills/"
```

For Claude Code:

```bash
mkdir -p "$HOME/.claude/skills"
cp -R japanese-writing-style "$HOME/.claude/skills/"
```

You can invoke the skill explicitly with `$japanese-writing-style`. Agents that
support implicit skill discovery can also select it when creating or editing
Japanese prose.

## License

The repository is available under the [MIT License](LICENSE).
