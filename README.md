<div align="center">

# Teguh Dwi Cahya Kusuma

**Backend &amp; platform engineer — Go, TypeScript, Python.**

I build the half of the product nobody screenshots: APIs, data models, gateways,
and the deployment plumbing that keeps a demo alive in production.

<sub>Yogyakarta, Indonesia &nbsp;·&nbsp; <a href="https://diama.dev">diama.dev</a> &nbsp;·&nbsp; <a href="mailto:teguh.dc.kusuma@gmail.com">teguh.dc.kusuma@gmail.com</a></sub>

</div>

---

## Currently

- Shipping a **multi-tenant hotel booking platform** — service API, guest webview, and chat in one repo.
- Building **Onesist** — traceability for system-analyst deliverables, so requirements stop living in three different documents.
- Running a **self-hosted lab** (Postgres, CI, Cloudflare tunnels, agent tooling) that most of my side projects ship through.

## The stack I actually run

```text
            ┌───────────────────┐
   clients ─┤    Cloudflare     │  DNS · Workers · tunnels · Turnstile
            └─────────┬─────────┘
                      │
            ┌─────────┴─────────┐
            │     services      │  Go · TypeScript · Python
            │  booking · HRIS   │  NestJS · Hono · chi
            └─────────┬─────────┘
                      │
            ┌─────────┴─────────┐
            │       data        │  PostgreSQL · Redis · Prisma · Drizzle
            └─────────┬─────────┘
                      │
            ┌─────────┴─────────┐
            │   ops & agents    │  systemd · CI · MCP · telemetry
            └───────────────────┘
```

Same layers whether it is a client product or a weekend experiment — the difference is
how much of each one I have to own.

## What I optimise for

- **Measure, then move.** Latency and throughput are requirements with numbers, not vibes; a gateway is only fast if someone wrote down the budget.
- **Boring infrastructure wins.** One Postgres, systemd units, and a tunnel you can inspect beat a cluster you cannot debug at 2 a.m.
- **One binary when possible.** For small services, a static build beats an orchestration layer — fewer moving parts means fewer things to restart at 3 a.m.
- **Small surfaces.** Fewer endpoints, fewer config flags, fewer abstractions — the cheapest code to maintain is the code that is not there.
- **Automate the repeat.** If I have done it twice by hand, it becomes a script, a pipeline, or a bot.

## Toolbox

| | |
|:--|:--|
| **Languages** | `Go` `TypeScript` `Python` `SQL` `C#` `Dart` |
| **Backend** | `NestJS` `Hono` `chi` `Prisma` `Drizzle` `PostgreSQL` `Redis` |
| **Frontend** | `Next.js (App Router)` `React` `Tailwind` `Zustand` |
| **Infra** | `Linux` `Docker` `Cloudflare Workers & Tunnels` `GitHub Actions` `Woodpecker` |
| **AI tooling** | `MCP servers` `agent harnesses` `backtesting & signal pipelines` |

## Elsewhere

- Open to freelance work on **backend architecture, multi-tenant platforms, and edge deployments**.
- Email is the fastest way to reach me: [teguh.dc.kusuma@gmail.com](mailto:teguh.dc.kusuma@gmail.com).
