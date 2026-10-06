# TROA NPC+ Public Roadmap

TROA NPC+ is in active pre-release development. This roadmap describes product milestones, not a delivery guarantee or release schedule. The public repository remains source-free and no installable build or supported command set is available.

## Milestones

1. **Server lifecycle foundation:** prove Torch load/unload, permission-checked status reporting, bounded server scheduling, persistent state, and clean restart recovery without changing the game world.
2. **First in-world slice:** add one server-owned NPC identity with a simple patrol. Validate spawn ownership, multiplayer replication, damage/death, save/restart reconciliation, cleanup, and fail-closed behavior when an engine capability is unavailable.
3. **Safe content authoring:** provide a validated, versioned content format and a reload path that keeps the last known-good content when new content is invalid.
4. **Expand gameplay in measured steps:** add encounters, squads, missions, faction behavior, reputation, and persistent consequences only after the prior world-interaction and recovery gates pass.

## Product direction

NPC+ is intended to support persistent identities, factions, missions, encounters, memory, and world history. The first announced TROA faction is the **Asgardian Concord**, commonly called the Asgardians. Public feature scope may change as implementation and server testing progress.

## Release gate

Before a public build, complete a dedicated-server soak with bounded entity and CPU budgets, restart recovery, multiplayer replication, safe content reload, and no orphaned NPC bodies or grids. Until then, there is no public installation package or support commitment.
