# DadaSchematicImporter 1.0

> Custom Minecraft plugin with dedicated commands and server-side features.

![Minecraft](https://img.shields.io/badge/Minecraft-1.20%2B-green?style=for-the-badge)
![Paper](https://img.shields.io/badge/Paper%20%2F%20Spigot-Compatible-blue?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0-purple?style=for-the-badge)

## Overview

**DadaSchematicImporter 1.0** is a custom Minecraft plugin for Paper/Spigot servers.

Custom Minecraft plugin with dedicated commands and server-side features.

| Field | Value |
| --- | --- |
| Plugin | `DadaSchematicImporter` |
| Version | `1.0` |
| Category | Custom Server Tool |
| Main class | `it.dadasmp.schematic.DadaSchematicImporter` |

## Features

| Feature | Description |
| --- | --- |
| Clean package | Public jar name without server-specific labels. |
| Server ready | Designed for Paper/Spigot Minecraft servers. |
| Configurable | Uses Bukkit/Paper plugin configuration where supported. |
| Commands | Includes in-game commands documented below. |

## Commands

| Command | Description | Usage | Permission | Aliases |
| --- | --- | --- | --- | --- |
| `/dadaimportsunken` | Importa la schematic Sunken Spire in un mondo di test. | `/dadaimportsunken [force]` | `dadaimportsunken.admin` | None |
| `/dadasunken` | Teletrasporta al mondo Sunken Spire importato. | `/dadasunken` | `dadaimportsunken.admin` | None |

## Permissions

No permissions are declared in `plugin.yml`.

## Installation

1. Download the jar from the `release` folder.
2. Put it inside your server `plugins` folder.
3. Restart the server.
4. Configure the plugin if it creates a configuration folder.

Compiled jar:

`release/DadaSchematicImporter-1.0.jar`

## Support

For support, bug reports or setup help, join the Discord server:

https://discord.gg/yXrDpKCGAs

## License

All rights reserved. Redistribution, resale or modification is not allowed without written permission from DadaSMP.
