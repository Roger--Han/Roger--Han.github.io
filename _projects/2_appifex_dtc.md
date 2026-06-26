---
layout: page
title: appifex-dtc — Design-to-App CLI
description: Open-source CLI — "design to TestFlight in one command." TypeScript · pnpm monorepo · MCP server.
img: assets/img/appifex-dtc.png
importance: 2
category: work
---

A CLI that generates compilable, linted native mobile apps from design files (Pencil / Figma / Stitch) — encoding native best practices for both platforms: SwiftUI on iOS, Kotlin Compose on Android.

- Design tokenization → platform spec generation → test scaffolding → LLM code generation → compile/validate → auto-fix loops → store deploy.
- Validation gating with Maestro UI tests and semgrep security scans.
- Checkpoint-based resume (SQLite) so interrupted runs continue without restarting.
- Pipeline stages exposed as MCP tools for AI-agent orchestration.

<a href="https://github.com/appifex-ai-org/appifex-dtc" target="_blank" rel="noopener">View on GitHub →</a>
