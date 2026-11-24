<div align="center">

# Aliaksei Patskevich · AVPdev

**Software Engineer · Solutions Architect**

Full-Stack · Backend · Product Development · Integrations & Automation

[Website](https://avpdev.com/) · [Blog](https://avpdev.com/en/blog/) · [LinkedIn](https://linkedin.com/in/avp-dev) · [Telegram](https://t.me/AVP_Dev)

**English** · [Русская версия](./README.ru.md)

</div>

## About

I design and build software products and business systems, from requirements and architecture to implementation, testing, and deployment.

My work covers full-stack and backend engineering, SaaS, APIs, integrations, infrastructure, and automation. I also develop AI-powered systems and open-source developer tools.

## Selected projects

| Project | Description |
| --- | --- |
| [Pravia](https://pravia.dev/) | B2B SaaS platform for AI assistants based on corporate knowledge, RAG and integrations. |
| [pair-mailbox](https://github.com/AVP-Dev/pair-mailbox) | Open-source MCP protocol for paired coding agents, with a single-writer invariant and patch integrity verification. Python, no external dependencies. |
| [NYX Vox](https://github.com/AVP-Dev/nyx-vox) | Desktop voice input, speech recognition and text formatting application built with Rust and Tauri. |
| [agent-starter-kit](https://github.com/AVP-Dev/agent-starter-kit) | Engineering standards, architectural guidelines and automated verification for AI-assisted development. |
| [AVPdev](https://avpdev.com/) | Personal portfolio, software development services and technical blog built with Astro, TypeScript and Bun. |

### In active development

**[TALOS](https://github.com/AVP-Dev/talos) — Early Beta**

Local Rust-based orchestrator for coding CLIs, with a terminal cockpit, role separation, change verification and Git integration.

*Early beta: bugs, unexpected behavior and functional changes are possible. Not yet recommended for mission-critical workflows.*

## Technology stack

| Area | Technologies |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, Go, Rust |
| Backend & APIs | Node.js, Bun, FastAPI, REST, OpenAPI, SSE, WebSockets |
| Frontend | Next.js, React, Astro, Tailwind CSS |
| Data & queues | PostgreSQL, Redis, SQLite, Drizzle ORM, BullMQ |
| Infrastructure | Docker, Linux, Nginx, GitHub Actions, Coolify, Dokploy |
| Desktop | Rust, Tauri, cpal |
| AI & automation | LLMs, RAG, pgvector, HNSW, ONNX Runtime, MCP, agent orchestration |
| Testing | Vitest, Playwright, k6 |

## Engineering approach

Clear contracts, explicit system invariants, pragmatic technology choices, security and automated verification.

For AI-assisted development, I use an approach called **Zero Vibe Coding**: an architectural foundation (Skeleton), explicit ownership boundaries and isolated, replaceable modules (Disposable Modules). Architectural decisions and responsibility remain with the engineer.

Read more on my [technical blog](https://avpdev.com/en/blog/).

## Terminal API

```bash
# ANSI banner and telemetry
curl -s "https://avpdev.com/api/connect?banner=1"
# Availability status
curl -s "https://avpdev.com/api/connect?raw=status"
# Collaboration
curl -s "https://avpdev.com/api/connect?action=hire"
```

---

<div align="center">

[avpdev.com](https://avpdev.com/) · [contact@avpdev.com](mailto:contact@avpdev.com)

</div>
