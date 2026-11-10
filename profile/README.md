# Faris Han Labs

A personal lab for building reliable, everyday tools — with zero vendor
lock-in. Shared openly, contributed back to the community.

## Vision

Big tech dependencies make tools fragile and hard to trust. This lab exists
to build small, dependable, day-to-day utilities that I actually use, that
anyone can self-host or fork, and that owe nothing to any single vendor.
Human + AI agents collaborate here: I set direction, agents execute and
iterate alongside.

## Flagship

- [`cockpit`](https://github.com/farishan-labs/cockpit) — the human+AI control
  plane. The first thing installed and opened when operating the lab. An
  aggregator, not a replacement: it reuses herdr, pi, opencode, nakama (ahmadrosid), tmux.

## What lives here

- [`principles`](https://github.com/farishan-labs/principles) — canonical, versioned principles (P-001..P-022) with top/core/extended tiers, format research, and management tooling (render, validate, version). Source of truth for cockpit and every tool. Research-first: each principle is backed by a research doc before it becomes a rule.

- Reliable, everyday tools I genuinely depend on
- Shared tooling, skills, and infrastructure for agent workflows
- Open-source contributions and experiments worth keeping

## What does *not* live here

Personal, hand-written (or AI-assisted-but-proudly-mine) code stays on the
personal account [`@farishan`](https://github.com/farishan).

## Principles

Canonical, versioned principles (P-001..) live in
[`principles`](https://github.com/farishan-labs/principles) — source of
truth. See there for the full list and tiers.

## Conventions

- Security: Dependabot alerts, security updates, dependency graph, and
  secret scanning are enabled by default for new repositories.
- Prefer small, focused repos over monoliths.

---
_Maintained by Faris Han and agents._
