---
name: ecc
description: ECC, the agent harness operating system for Claude Code and adjacent agent harnesses. Entry point to the ECC plugin: skills, commands, agents, hooks and rules declared by the plugin manifest.
---

# ECC plugin

This repository is the ECC plugin. Its authoritative manifest is `.claude-plugin/plugin.json` (plugin name `ecc`, version 2.2.3). If an installer cannot read the hidden `.claude-plugin` directory, this file declares the same components so the plugin still validates.

Components declared by the manifest:

- Skills: `./skills/` — 311 skills, each in its own directory with a SKILL.md file.
- Commands: `./commands/` — 97 slash commands as Markdown files.
- Agents: `./agents/`
- Hooks: `./hooks/`
- Rules: `./rules/`
- Marketplace: `.claude-plugin/marketplace.json` — marketplace name `ecc`, containing the plugin `ecc` with source `./`.
