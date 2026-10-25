> [!NOTE]
> **This skill now lives in the main collection: [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills/tree/main/skills/competitor-spy)**. Please ⭐ star it there; that's where updates land first.
> Docs: **https://milad-ahmd.github.io/agent-skills/skills/competitor-spy/** · Claude Code: `/plugin install all-skills --marketplace milad-ahmd/agent-skills`

<div align="center">

# 🕵️ competitor-spy

**Competitor analysis of pricing, messaging, socials, ads and reviews, with a SWOT and opportunities. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/competitor-spy)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/competitor-spy?style=social)](https://github.com/milad-ahmd/competitor-spy)
![Category](https://img.shields.io/badge/category-Marketing-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/competitor-spy/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- competitor-spy
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/competitor-spy /tmp/competitor-spy
mkdir -p ~/.claude/skills && cp -r /tmp/competitor-spy/skills/competitor-spy ~/.claude/skills/
```

**Per project:** copy `skills/competitor-spy` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/competitor-spy/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Analyze my top 3 competitors
Find gaps in our competitors' marketing
```

The full workflow, rules and output format are in [`SKILL.md`](skills/competitor-spy/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
