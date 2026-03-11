<div align="center">

<img width="1920" height="1080" alt="VIPEX-MDT V2 Thumbnail" src="https://github.com/user-attachments/assets/1a323dda-155d-4ee2-b285-f8bd1dc2f98b" />

<br />

# VX_MDT

A modern, performance-focused mobile data terminal for FiveM.

[![Version](https://img.shields.io/github/v/release/vipex-dev/vx_mdt)](../../releases/latest)
[![FiveM](https://img.shields.io/badge/FiveM-Cerulean-orange)]()
[![Lua](https://img.shields.io/badge/Lua-5.4-purple)]()
[![Svelte](https://img.shields.io/badge/Svelte-5-ff3e00)]()

[Purchase](https://store.vipex.dev/package/mdt) | [Documentation](https://docs.vipex.dev) | [Discord](https://discord.gg/TX5qWWk7Wq)

</div>

---

## About

vx_mdt is a fully-featured mobile data terminal built with a modern tech stack (Svelte 5, Lua 5.4, TypeScript) and designed for serious roleplay communities. It supports multiple frameworks out of the box and integrates deeply with existing server ecosystems.

This repository is used for **version tracking** and **bug reports / feature requests** only. The source code is not hosted here.

## Features

- **Profiles** — citizen records with linked vehicles, incidents, warrants, licenses, images, and tags
- **Dispatch** — real-time call management with panic button, radio auto-tuning, and third-party dispatch compatibility
- **Incidents & Reports** — detailed records with involved persons, evidence linking, and vehicle tracking
- **BOLO & Warrants** — person and vehicle BOLOs with active status tracking
- **Charges & Sentencing** — multi-charge application with severity tiers, fines, and jail time
- **Evidence** — stash tracking, property linking, chain of custody
- **Vehicles & Weapons** — registration, status flags (stolen/seized/impounded), plate and serial lookups
- **Templates** — pre-built report forms with markdown support for one-click insertion
- **Dashboard** — live stats, bulletin board, active units, recent activity
- **Rich Text Editor** — TipTap-based editor with @mentions and formatting
- **Cross-Department Sharing** — share records as viewer or collaborator across departments
- **Multi-Department** — law enforcement, EMS, and judicial branches with type-specific UI and config
- **Rank & Permission System** — drag-to-reorder ranks with granular permissions
- **Roster Management** — callsigns, badge numbers, certificates, licenses, department assignment
- **30+ Server Exports** — full API for external resources to interact with the MDT programmatically

## Supported Frameworks

| Framework  | Status    |
| ---------- | --------- |
| QBX (QBox) | Supported |
| QB-Core    | Supported |
| ESX        | Supported |
| ox_core    | Planned   |

Integrates with ox_inventory, ox_lib, pma-voice, and [many more](https://docs.vipex.dev).

## Requirements

- FiveM server build 17000+
- OneSync
- ox_lib
- oxmysql
- MySQL / MariaDB

## Issues

Use the [Issues](../../issues) tab to report bugs or request features. Please include:

- **Server framework** (QBX, QB-Core, ESX)
- **Resource version** (check with `ensure vx_mdt`)
- **Steps to reproduce** the issue
- **Screenshots or logs** if applicable

## Links

- [Purchase](https://store.vipex.dev/package/mdt)
- [Documentation](https://docs.vipex.dev)
- [Discord](https://discord.gg/TX5qWWk7Wq)
