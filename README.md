# Vilse

Vilse is a long-term civilization MMO project about entering an industrial world
that is already running: cities, depots, markets, permits, archives,
infrastructure, logistics, labor pressure, and institutions before the player
arrives.

This repository is a public mirror for product transparency and project updates.
It intentionally does **not** contain source code, backend logic, prompts,
datasets, deployment configuration, or implementation details that would make
the private prototype cloneable.

## Current Status

As of June 25, 2026, Vilse is a private prototype, not a released game and not a
public test build.

The private implementation currently demonstrates a dense Confluence Basin demo
slice with:

- a server-authoritative hauling loop from public work board to pickup,
  delivery, and payout
- actor-visible records for markets, notices, permissions, compliance,
  construction, labor, research, production, vehicle service, archives, and
  infrastructure
- a legacy 3D prototype used as reference material for field interaction and
  institutional UI
- an active 2D/2.5D MVP client direction intended to prove the same world
  through map movement and dense data panels
- a protocol direction that treats clients as projections over server-owned
  world state

What is **not** implemented yet: a public build, production persistence, real
MMO concurrency, broad multi-region geography, player-run institutions at scale,
or a shipped game economy.

## Product Direction

Vilse is built around a different MMO premise:

- the world is not a blank survival reset
- information is not omniscient; it comes from records, publications, registries,
  offices, and trust relationships
- infrastructure and logistics are gameplay, not background scenery
- institutions, permits, finance, labor, and maintenance create leverage
- moment-to-moment play should stay readable while the systems underneath remain
  deep

The first goal is not geographic size. The first goal is one dense region where
the systems prove they can interact honestly.

## Why This Mirror Exists

This public mirror gives a controlled view of the project without exposing the
private repository. It is meant for:

- public positioning
- project status
- high-level architecture
- roadmap transparency
- licensing and reuse boundaries

It is not an open-source release and not a source-available build.

## Documents

- [ARCHITECTURE.md](ARCHITECTURE.md) — high-level architecture without private implementation details
- [ROADMAP.md](ROADMAP.md) — truthful public roadmap and current limitations
- [SECURITY.md](SECURITY.md) — reporting and disclosure expectations
- [FAQ.md](FAQ.md) — public-surface questions
- [CONTRIBUTING.md](CONTRIBUTING.md) — contribution posture
- [NOTICE.md](NOTICE.md) — all-rights-reserved notice

## Reuse

No permission is granted to copy, modify, redistribute, host, resell, or use this
work or any substantial part of it in a competing product or service without
explicit written permission.
