# TROA NPC+

> **Coming soon:** a server-authoritative NPC simulation framework for Torch-powered Space Engineers dedicated servers.

TROA NPC+ is being built to make persistent, story-aware NPC activity possible without treating a spawned grid or character as the NPC itself. The platform is designed around durable identities, faction state, missions, encounters, memory, and world history—then connects those systems safely to a Torch and Space Engineers server.

## What is planned

- Persistent NPC identities that can exist virtually, as characters, as grids, or as fleet and squad commanders.
- A server-authoritative simulation layer with performance-aware scheduling and safe interaction with the game world.
- Dynamic encounters, missions, faction activity, territory, reputation, and consequences that reflect server history.
- Data-driven content packs so communities can author their own factions, lore, fleets, encounters, and campaigns.
- A first-party TROA faction: **The Asgardians**, the Asgardian Concord.
- A versioned integration surface for compatible server-side plugins, designed to avoid unsafe direct state changes.

## Status

NPC+ is in active pre-release development. There is no public build, installation package, release date, or support commitment yet. Features and priorities may change as implementation and server testing progress.

This repository intentionally contains public project information only. It does not include source code, development builds, private configuration, game assets, or unreleased integration contracts.

## Platform target

- Space Engineers Dedicated Server
- Torch
- .NET Framework 4.8, x64

## Follow development

Watch this repository for public milestones, release notes, and eventual installation guidance. For the planned direction, see [the public roadmap](docs/ROADMAP.md).

## Project boundaries

TROA NPC+ is a server-side project. Any future client requirements, compatibility information, and distribution terms will be documented with an actual release.

## License and use

Copyright © 2026 TROA Inc. All rights reserved. No license to use, copy, modify, distribute, or reverse engineer unreleased project materials is granted by this repository.
