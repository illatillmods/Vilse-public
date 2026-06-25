# Public Roadmap

This roadmap is intentionally conservative. It describes direction and current
status without implying that the private prototype is a shipped MMO.

## Current Private Prototype

Verified current state:

- dense Confluence Basin demo slice
- server-authoritative work-board to delivery to payout loop
- actor-scoped records for markets, compliance, permits, construction, labor,
  research, production, vehicle service, infrastructure, heritage, and archives
- legacy 3D prototype used as reference material
- early 2D/2.5D MVP client scaffold
- lightweight networking and session seams, not production MMO concurrency

Known limitations:

- no public build
- no production persistent world
- no real multiplayer scale
- no broad multi-region gameplay
- no final art pass
- no full player-run institutional economy

## Near-Term Direction

1. Harden the private prototype around one dense playable region.
2. Keep the server authoritative and the client presentation-only.
3. Move the MVP client toward a readable 2D/2.5D map plus dense institutional
   panels.
4. Preserve the protocol boundary so future clients can render the same world
   state.
5. Replace demo persistence with durable event/snapshot storage only after the
   core loop remains stable.

## Later Direction

- real account and multiplayer authority
- stronger persistence, replay, and recovery guarantees
- deeper markets, organizations, permits, labor, construction, and maintenance
- broader regions only after the first region is fun and reliable
- higher-fidelity 3D presentation after the systemic MVP proves itself

## Not Promised Here

This public mirror does not promise release dates, public testing dates,
fundraising terms, platform commitments, scale numbers, or performance
benchmarks.
