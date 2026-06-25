# Vilse

Vilse is an MMO project about arriving late.

The world is already running when the player enters it: depots have schedules,
markets have memory, public offices have records, infrastructure has owners,
permits have consequences, and the useful truth is rarely sitting in one
omniscient UI.

This repository is a public mirror for product transparency. It does not contain
the private source code, game client, server, maps, prompts, datasets, deployment
configuration, or implementation detail needed to reproduce the prototype.

## Snapshot

As of June 25, 2026, Vilse is a private prototype, not a released game, public
test build, open-source project, or playable public demo.

The private implementation currently proves a dense Confluence Basin slice:

- server-authoritative hauling from public work board to pickup, delivery, and
  payout
- actor-visible records for markets, notices, permissions, compliance,
  construction, labor, research, production, vehicle service, archives, and
  infrastructure
- a legacy Godot 4 prototype that remains reference material for the 3D field
  slice, HUD, vehicle pass, and world-surface interaction
- an active 2D/2.5D MVP direction using a Bevy + egui client scaffold against
  the current backend
- Rust protocol, persistence, and bot scaffolds that are not yet the primary
  simulation runtime
- a protocol direction where clients are projections over server-owned world
  state, not holders of gameplay authority

Not implemented yet: a public build, production persistence, real MMO
concurrency, broad multi-region geography, player-run institutions at scale, or
a shipped economy.

## What Makes Vilse Different

Vilse is not a blank survival reset with a market board attached. The design bet
is a civilization simulation where paperwork, transport, finance, institutional
trust, and infrastructure are gameplay.

Core principles:

- The world has history before the player arrives.
- Information comes from records, notices, publications, registries, offices,
  audits, and relationships.
- Logistics and maintenance are first-class systems, not background scenery.
- Institutions create leverage, friction, corruption, safety, and opportunity.
- The field experience must stay readable even when the underlying simulation is
  deep.

The first public-safe goal is not a huge map. It is one dense region where these
systems interact honestly.

## The Current Slice

The private demo is centered on useful work instead of spectacle:

1. Read a public freight posting.
2. Accept a contract under server-owned rules.
3. Move goods through a transport graph.
4. Deliver, get paid, and see the payout become a record.
5. Read the institutions around the route: permits, markets, public notices,
   compliance pressure, infrastructure state, and local history.

The important part is not the hauling itself. It is that hauling touches records,
authority, money, access, and place.

## Mirror Contents

- [ARCHITECTURE.md](ARCHITECTURE.md) - high-level architecture without private implementation details.
- [ROADMAP.md](ROADMAP.md) - public roadmap, current limits, and staged ambition.
- [SECURITY.md](SECURITY.md) - reporting and disclosure expectations.
- [FAQ.md](FAQ.md) - public-surface questions.
- [CONTRIBUTING.md](CONTRIBUTING.md) - contribution posture.
- [NOTICE.md](NOTICE.md) - all-rights-reserved notice.
- [assets/](assets/) - reserved for reviewed public media only.

## Reuse Boundary

This mirror is not a source-available release. No permission is granted to copy,
modify, redistribute, host, resell, or use Vilse or any substantial part of it in
a competing product or service without explicit written permission.
