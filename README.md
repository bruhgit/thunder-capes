# Thunder Cape & Skin Network

Official multiplayer cape and skin synchronization network for **Thunder Client & Thunder Launcher**.

## Overview
This repository serves as the high-availability global CDN for custom Minecraft capes and skins. When two or more Thunder Client players join the same multiplayer server, they instantly see each other's custom capes and skins in real-time.

- **Cape CDN Endpoint:** `https://raw.githubusercontent.com/bruhgit/thunder-capes/main/capes/{username}.png`
- **Skin CDN Endpoint:** `https://raw.githubusercontent.com/bruhgit/thunder-capes/main/skins/{username}.png`
- **Client Artifact:** `https://github.com/bruhgit/thunder-capes/raw/main/release/thunder-cape-client.jar`

## Compatibility
Supported across all environments:
- **Vanilla Minecraft** (via Universal Java Agent `-javaagent:thunder-cape-client.jar`)
- **Fabric & Quilt** (via `thunder-cape-client.jar` in `mods/`)
- **Forge & NeoForge** (via `CustomSkinLoader` or Java Agent)
- **OptiFine**
- **Minecraft Versions:** 1.7.10 through 1.21.x
