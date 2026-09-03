# Tyler

Solo founder building a portfolio of products and the open source underneath them. Active priorities: **Tebian**, **Neutron**, **Teploy**, **Fylun**. Below: the public projects, research, and tools that feed into those or stand on their own.

## Active priorities

| Project | What it is |
| --- | --- |
| [Tebian](https://tebian.org) | Debian usability layer — Sway + a bash puzzle menu that builds the OS with you, from containers to VMs to security to gaming. Strips back to plain Debian server by deleting a folder. |
| [Neutron](https://neutron.build) | One framework across web, mobile, desktop, and AI — in Rust, TypeScript, Mojo, Go, Zig, and Python. Backed by Nucleus, a 9-model database engine speaking PostgreSQL. |
| [Teploy](https://teploy.com) | Zero-downtime Docker deploys to any server via SSH. Single binary, no management server. Optional UI. Solves the SSH/UI state-desync problem in Dokploy and Coolify. Ecosystem: arcade (game servers), ship (coding agent), gateway (AI gateway), observe (observability). |
| [Fylun](https://fylun.ai/) | Unified AI platform — one subscription, one interface, replacing the need to juggle multiple AI services. Terminal agent: [fylun-code](https://github.com/usefylun/fylun-code). |

## Linux desktop play

The stack around Tebian for macOS-refugee Linux users — wedge, environment, and the analysis that scopes it.

| Project | Role | Status |
| --- | --- | --- |
| [maccel](https://github.com/im-tyler/maccel) | Mouse acceleration daemon — brings macOS pointer feel to any compositor (Sway, Hyprland, Cosmic, X11) | early development |
| [Haven](https://github.com/im-tyler/haven) | Desktop environment for macOS refugees — dock, top bar, Spotlight-style launcher, native mouse feel | design phase |

## Selected public work

- [lullmail](https://github.com/lullmail/lullmail) — Briefing-first mail client: senders screened once and routed forever, a daily briefing of what actually needs you, board/calendar/notes that derive themselves from mail. One Go binary + Postgres, AGPL. Site at [lullmail.com](https://lullmail.com).
- [omni-analyst](https://github.com/omnianalyst/omni-analyst) — Self-hosted market intelligence. Demand-driven coverage, calibrated conviction, and a public record of every prediction it ever made.
- [light-system](https://github.com/im-tyler/light-system) — Renderer competing with Nanite and Lumen, plus a modified PhysX 5.6 implementation for unified physics simulation. Vulkan and WebGPU.
- [omilator](https://github.com/im-tyler/omilator) — Cross-platform libretro frontend in Kotlin Multiplatform + Compose (macOS, Windows, Linux, iOS, Android).
- [babel-bible](https://github.com/im-tyler/babel-bible) — Omnidisciplinary self-study curriculum (math, physics, chemistry, biology, philosophy, language, social science) with Lean 4 formalization. Companion site at [babelbible.org](https://babelbible.org).
- [simval](https://github.com/im-tyler/simval) — Deterministic verification oracle for computational-physics simulations. Local-first, LLM-free core.
- [agent-inbox](https://github.com/im-tyler/agent-inbox) — Federated supervisor for CLI coding agents. One inbox holding N independent projects, each with its own long-lived Claude Code or OpenCode session.
- [omi-rss](https://github.com/im-tyler/omi-rss) — RSS reader: Flutter app + browser extension + backend server.
- [kkt-framework](https://github.com/im-tyler/kkt-framework) — KKT Geodesic Framework: Klein bottle Kaluza-Klein theory with a₀ = cH₀/(2π) — code, data, and verification scripts.

## Stack

[![Neutron](https://img.shields.io/badge/Neutron-7C3AED)](https://github.com/neutron-build/neutron)
[![Nucleus](https://img.shields.io/badge/Nucleus-2563EB)](https://github.com/neutron-build/neutron)
[![Teploy](https://img.shields.io/badge/Teploy-0D9488)](https://github.com/useteploy/teploy-cli)
