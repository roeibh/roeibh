<div align="center">

# Roei

*AppSec × AI — agentic systems that reason about vulnerabilities, and tooling that makes coding agents behave*

[![Claude Code skills](https://img.shields.io/badge/Claude_Code-skills-D97757?style=flat-square)](https://github.com/search?q=user%3Aroeibh+topic%3Aclaude-skills&type=repositories)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Node.js](https://img.shields.io/badge/Node.js-3c873a?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org)
[![AWS](https://img.shields.io/badge/AWS-232f3e?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com)

[Claude Code skills](#claude-code-skills) • [Other tools](#other-tools) • [Install](#install)

</div>

I spend my days on application security and AI — building systems that reason about
vulnerabilities instead of pattern-matching them. Before that: security research, reverse
engineering, and a long stretch in automation.

Most of that work lives in private repos. What's here is the other half — the tooling I build
because I got tired of fighting my own coding agents.

> [!NOTE]
> These are opinionated. They encode how *I* think code should be written and reviewed.
> Fork and adjust rather than assuming the defaults suit you.

## Claude Code skills

| Skill | What it does |
| --- | --- |
| **[human-comments](https://github.com/roeibh/human-comments)** | Stops agents writing essay comments. Almost none survive, and the ones that do are fragments a senior engineer would actually leave. Ships as a Claude skill *and* a Cursor rule. |
| **[interactive-spec](https://github.com/roeibh/interactive-spec)** | Turns a written spec into a clickable HTML mockup, then pipes your inline comments back to Claude. A closed review loop, not a one-shot mockup. |
| **[marp-deck-architect](https://github.com/roeibh/marp-deck-architect)** | Builds Marp decks from four archetypes — Builder, Operator, Storyteller, Educator — that shape not just the theme, but how the deck gets written. |
| **[interviewer-kit](https://github.com/roeibh/interviewer-kit)** | Turns a job description into a reusable interview template, then personalises it per candidate. |
| **[morning-briefing](https://github.com/roeibh/morning-briefing-claude-plugin)** | Triages inbox, calendar and industry noise into one briefing with draft replies and ranked priorities. |

## Other tools

| Project | What it does |
| --- | --- |
| **[check-please](https://github.com/roeibh/check-please)** | Your chess.com games, opened in Lichess's engine. No signup, no paywall, no server — static files running in your browser. **[Try it →](https://roeibh.github.io/check-please/)** |
| **[reload-window](https://github.com/roeibh/reload-window)** | A reload-window button in the VS Code status bar. Solves exactly one problem, completely. |
| **[improve-prompt](https://github.com/roeibh/improve-prompt)** | CLI that rewrites a rough prompt into a better one. Works with any OpenAI-compatible API. |

## Install

`human-comments` and `interactive-spec` are a clone away:

```bash
git clone https://github.com/roeibh/<skill> ~/.claude/skills/<skill>
```

> [!IMPORTANT]
> The rest differ. **interviewer-kit** installs as `interview-prep` (that name is the slash command),
> **marp-deck-architect** also drops a command into `~/.claude/commands/`, and **morning-briefing**
> is a Cowork plugin needing Claude in Chrome. Each repo's README has the exact steps.

<div align="center">

:star: If one of these saves you an afternoon, star it — it's how the next person finds it.

</div>
