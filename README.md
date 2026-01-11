# Agent Skills CLI 🚀

> **One CLI. 50,000+ skills. All AI agents.**

[![npm version](https://img.shields.io/npm/v/agent-skills-cli)](https://www.npmjs.com/package/agent-skills-cli)
[![license](https://img.shields.io/npm/l/agent-skills-cli)](LICENSE)

Install skills from the world's largest marketplace and sync them to **Cursor**, **Claude Code**, **GitHub Copilot**, **OpenAI Codex**, and **Antigravity** — all with a single command.

🌐 **Website:** [agentskills.in](https://agentskills.in)

```bash
npm install -g agent-skills-cli
skills install @anthropic/xlsx
```

---

## ✨ Features

- **50,000+ Skills** — Access the largest collection of AI agent skills
- **5 AI Agents** — Works with Cursor, Claude, Copilot, Codex, Antigravity
- **Platform Targeting** — Install to specific platforms with `-t claude,cursor`
- **Auto-Detection** — Automatically detects installed AI agents
- **Interactive CLI** — Arrow-key navigation, search, and progress spinners

---

## 📦 Installation

```bash
npm install -g agent-skills-cli
```

**Requirements:** Node.js 18+

---

## 🚀 Quick Start

```bash
# Install a skill (auto-detects platforms)
skills install xlsx

# Install to specific platforms
skills install @anthropic/pdf -t claude,cursor

# Install to all platforms
skills install docx --all

# Search the marketplace
skills search "machine learning"

# List installed skills
skills list
```

---

## 🛠️ Commands

### Core Commands

| Command | Description |
|---------|-------------|
| `skills install <name>` | Install a skill from marketplace |
| `skills list` | List installed skills |
| `skills search <query>` | Search the marketplace |
| `skills show <name>` | Show skill details |
| `skills update` | Update installed skills |
| `skills doctor` | Diagnose issues |

### Install Options

```bash
skills install <name>              # Auto-detect platforms
skills install <name> -t claude    # Install to Claude only
skills install <name> -t cursor,copilot  # Install to multiple
skills install <name> --all        # Install to all platforms
```

### Other Commands

```bash
skills init <name>        # Create new skill from template
skills validate <path>    # Validate a SKILL.md file
skills export             # Export skills to agents
skills sync               # Sync to Antigravity workflows
skills info               # Show installation status
```

---

## 🤖 Supported Platforms

| Platform | Directory | Flag |
|----------|-----------|------|
| **Cursor** | `.cursor/skills/` | `-t cursor` |
| **Claude Code** | `.claude/skills/` | `-t claude` |
| **GitHub Copilot** | `.github/skills/` | `-t copilot` |
| **OpenAI Codex** | `.codex/skills/` | `-t codex` |
| **Antigravity** | `.agent/workflows/` | `-t antigravity` |

---

## 📚 Creating Skills

Create a `SKILL.md` file:

```markdown
---
name: my-skill
description: What this skill does
---

# Instructions

Your skill instructions here...
```

Then install locally:

```bash
skills validate ./my-skill
skills export
```

---

## 🔗 Links

- **Website:** [agentskills.in](https://agentskills.in)
- **Marketplace:** [agentskills.in/marketplace](https://agentskills.in/marketplace)
- **Documentation:** [agentskills.in/docs](https://agentskills.in/docs)
- **CLI GitHub:** [github.com/Karanjot786/agent-skills-cli](https://github.com/Karanjot786/agent-skills-cli)
- **Website GitHub:** [github.com/Karanjot786/agent-skills-UI](https://github.com/Karanjot786/agent-skills-UI)
- **npm:** [npmjs.com/package/agent-skills-cli](https://www.npmjs.com/package/agent-skills-cli)

---

## 👤 Author

**Karanjot Singh**

- 🐦 [@Karanjotdulay](https://x.com/Karanjotdulay)
- 💼 [LinkedIn](https://www.linkedin.com/in/karanjot786/)
- 🐙 [@Karanjot786](https://github.com/Karanjot786)

---

## 📄 License

MIT © [Karanjot Singh](https://github.com/Karanjot786)
