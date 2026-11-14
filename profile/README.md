# Faris Han Labs

Personal lab for reliable, everyday tools — zero vendor lock-in.

## Flagship

- [`mdview`](https://github.com/farishan-labs/mdview) — native markdown viewer (Python+GTK3+WebKit2, fullscreen borderless, TOC+search). The flagship desktop tool.

- [`gidbams`](https://github.com/farishan-labs/gidbams) — production-ready
  git-as-a-source-of-truth database engine. Treats a Git repository as the
  authoritative store; records are plain text files, reviewed via PRs and
  versioned by commits, queried via a derived SQLite cache and an MCP server.
  The SSOT layer underneath providers, forager, provider-intel, and others.

## What lives here

- [`principles`](https://github.com/farishan-labs/principles) — canonical, versioned principles (P-001..P-022) with top/core/extended tiers, format research, and management tooling (render, validate, version). Source of truth for cockpit and every tool. Research-first: each principle is backed by a research doc before it becomes a rule.

- Reliable, everyday tools I genuinely depend on
- Incubating: [`cockpit`](https://github.com/farishan-labs/cockpit) (human+AI control plane; paused, herdr-app is the daily driver)
- Shared tooling, skills, and infrastructure for agent workflows
- Open-source contributions and experiments worth keeping

## Conventions

- Security: Dependabot alerts, security updates, dependency graph, and
  secret scanning are enabled by default for new repositories.
- Prefer small, focused repos over monoliths.

---
_Maintained by Faris Han and agents._
