# Public Architecture Overview

This overview describes Vilse at a product and systems level. It deliberately
omits source code, schemas, algorithms, prompts, deployment details, and private
implementation choices.

## Core Principle

The world is the authority. Clients are presentation layers.

Vilse is designed so accounts, contracts, inventories, permissions, records,
markets, infrastructure state, and historical consequences live server-side.
Renderers can change over time without making player progress depend on a
single client implementation.

## Runtime Shape

The current private prototype is organized around these boundaries:

- **Authoritative world service:** owns simulation state, action validation,
  visibility, and actor-scoped read models.
- **Information layer:** exposes what an actor can plausibly know through
  boards, notices, registries, offices, publications, and trust/freshness
  metadata.
- **Projection clients:** render world state, movement feel, maps, panels, and
  interaction affordances without owning gameplay truth.
- **Protocol boundary:** separates public world state, actor-specific state,
  presentation hints, and advertised action authority.
- **Persistence target:** durable event and snapshot storage is part of the
  long-term architecture, but the current prototype is not yet a production
  persistent MMO.

## Current Proof

The private prototype proves the architecture through one dense region rather
than fake planet-scale breadth. The implemented demo slice ties hauling,
markets, compliance, permits, public records, construction, labor, research,
production, vehicle service, infrastructure, and archives into one authoritative
world model.

Many of those systems are seeded showcase lanes, not full player professions or
complete economies. Their value is that they share the same state boundaries and
information doctrine instead of existing as disconnected menus.

## Design Constraints

- The client must not become a hidden gameplay authority.
- Public UI should avoid universal truth claims; records need source, scope,
  freshness, and trust context.
- Dense simulation is preferred over broad geography until the core loop is
  proven.
- Long-term 3D presentation should be additive over the same world state, not a
  rewrite of the game.

## Excluded From This Mirror

The public mirror does not include backend code, client code, protocol schemas,
AI prompts, private planning notes, deployment manifests, datasets, ranking or
scoring logic, internal tooling, or security-sensitive details.
