# ZyveraRewards# Zyvera-Rewards

A lightweight daily reward system plugin for Paper servers (1.16+).

Configurable GUI with MiniMessage gradient support, custom head textures, individual cooldowns, and per-reward permissions.

---
## Commands

| Command | Description | Permission |
|---------|-------------|------------|
| `/rewards` | Open the rewards GUI | `zyverarewards.use` |
| `/rewards reload` | Reload configuration | `zyverarewards.admin` |

**Aliases:** `/reward`, `/dailyrewards`, `/dr`

## Permissions

| Permission | Description | Default |
|------------|-------------|---------|
| `zyverarewards.use` | Open the rewards GUI | `true` |
| `zyverarewards.admin` | Reload config | `op` |
| `zyverarewards.claim.daily` | Claim daily reward | `true` |
| `zyverarewards.claim.weekly` | Claim weekly reward | `true` |
| `zyverarewards.claim.premium` | Claim premium reward | `op` |
## Requirements

- **Java** 17+
- **Paper** 1.16.5+ (or any Paper fork like Purpur)
- No additional dependencies required
## Installation

1. Download or build the JAR
2. Place it in your server's `plugins/` folder
3. Start/restart the server
4. Edit `plugins/Zyvera-Rewards/config.yml` to customize
5. Use `/rewards reload` to apply changes

---

**Authors:** Zyvera-Systems, Thomas U.
