# NPC+ — public project status and future operator guide

## Current public availability

NPC+ is a pre-release project. This public repository is source-free documentation; it currently does not provide an installable plugin package, supported gameplay NPC behavior, or a player command set. Do not download files from this documentation repository as a plugin. The only currently documented Torch status command is `!npc status` in the private development target; it reports integration/capability readiness and is not proof that NPC spawning or gameplay features are released.

## Planned system shape

The private design describes a Torch-hosted NPC framework with a narrow API for other TROA plugins, content packs, server-owned encounter definitions, NPC/faction/mission concepts, and staged support for world characters and grids. Roadmap entries are plans, not delivered features. Public docs will be updated when an actual versioned package exposes user-configurable behavior.

## When a public release is available

The server owner guide will specify supported Torch/game versions, package installation, first-run config and data directories, content-pack setup and schema validation, permissions, commands, API integration, and recovery procedures. Until those artifacts and release notes are published, there is no supported setup sequence to follow.

## Current best action

Watch the [README](../README.md) and [roadmap](ROADMAP.md) for release status. Do not point a production server at the private build, treat the roadmap as an API contract, or enable undocumented NPC behavior. Ask TROA for supported-release information if you need a package today.
