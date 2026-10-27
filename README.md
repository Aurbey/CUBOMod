# CUBOMod

Server-side Fabric mod powering the virtual economy, player progression, and live-ops telemetry for [CUBOMetre](https://cubometre.online). Zero client mods required.

[![Platform](https://img.shields.io/badge/platform-cubometre.online-334155?style=flat-square&labelColor=1e293b)](https://cubometre.online)
[![Runtime](https://img.shields.io/badge/runtime-Fabric%20%7C%20Java%2025-334155?style=flat-square&labelColor=1e293b)](https://github.com/Aurbey/CUBOMod)

### Context

Built to eliminate mod bloat and tick latency on the CUBOMetre multiplayer server. Instead of chaining dozens of conflicting third-party Fabric mods and compatibility workarounds, CUBOMod implements server-side gameplay, economy, and telemetry natively inside a unified Fabric Java pipeline.

### Systems

- **Virtual Economy & Banking:** "Blocks" virtual currency engine with player accounts, shop transactions, cooldown managers, and audit logging.
- **Progression & Retention:** Tiered level-up tracks, automated playtime rewards, advancement milestones, and custom scoreboard stats.
- **Server-Side QoL Mechanics:** Portable shulker inventory access directly in-hand with dupe-prevention nesting guards, custom boat jump physics, parkour checkpoints, and world labels.
- **Role & Team Synchronization:** Dynamic synchronization between LuckPerms permission groups and Vanilla Scoreboard Teams for tablist colors, sorting, and prefixes without external chat formatting plugins.
- **Live-Ops Telemetry:** Asynchronous event streaming for logins, player transactions, deaths, and achievements piped to external Discord bot bridges.
- **Network Compatibility:** Native support for Velocity modern forwarding (FabricProxy-Lite) and Text Placeholder API.

### Tech Stack

- **Platform:** Dedicated Minecraft Fabric Server (Java 25)
- **APIs:** Fabric API, LuckPerms API, PlaceholderAPI, Brigadier Commands
- **Proxy Layer:** Velocity Modern Forwarding

---
Developed by [Denis (Aurbey)](https://github.com/Aurbey) for [CUBOMetre](https://cubometre.online).
