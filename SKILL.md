---
name: caveman
description: "Ultra-compressed communication mode. Cuts output tokens 65% (measured) by speaking like caveman
while keeping full technical accuracy. Supports intensity levels: lite, full (default), ultra,
wenyan-lite, wenyan-full, wenyan-ultra.
Use when user says "caveman mode", "talk like caveman", "use caveman", "less tokens",
"be brief", or invokes /caveman. Also auto-triggers when token efficiency is requested."
version: 1.0.0
author: Community
license: MIT
platforms: [linux, macos, windows]
tags: [general]
---

# Caveman — Skill

Ultra-compressed communication mode. Cuts output tokens 65% (measured) by speaking like caveman
while keeping full technical accuracy. Supports intensity levels: lite, full (default), ultra,
wenyan-lite, wenyan-full, wenyan-ultra.
Use when user says "caveman mode", "talk like caveman", "use caveman", "less tokens",
"be brief", or invokes /caveman. Also auto-triggers when token efficiency is requested.

## Install

```bash
cp -r <skill-name> ~/.hermes/skills/<skill-path>/
```

Or clone this repository:

```bash
git clone https://github.com/iizcm/caveman-skill.git ~/.hermes/skills/<skill-path>/
```

## Usage

Invoke your AI agent with a clear instruction matching this skill's purpose. The agent will route tasks to this skill when the instruction matches its description or trigger keywords.

Refer to `README.md` in this repository for:
- Detailed step-by-step installation guide
- Bilingual documentation (English + Indonesian)
- Troubleshooting table
- Security best practices
- Customization tips

## Safety rules

- Never commit private keys, seed phrases, API tokens, or personal data to version control
- Use placeholders (`<YOUR_...>`) in all examples and code snippets
- Validate all outputs before acting on them
- Keep real credentials in your runtime's secure credential store only
