# Jason Marshall

Systems builder focused on durable software, operational clarity, and human-centered tooling.

I build production systems, developer tools, creator infrastructure, and business platforms designed to survive real-world use without becoming fragile or over-engineered.

My work sits at the intersection of:
- operational software
- local-first and privacy-conscious tooling
- creator infrastructure
- deployment and systems reliability
- human-readable workflows over abstraction-heavy complexity

> Ship clear systems. Reduce ambiguity. Stop when it’s correct.

---

## Current Focus

### JAMARQ Digital
Production-grade business systems, operational infrastructure, and custom software.

Focused on:
- real-world deployment reliability
- admin tooling
- media and workflow systems
- environment-safe delivery
- long-term maintainability
- local-first desktop apps with explicit human oversight

Software currently includes:
- operational coordination tools
- AI-assisted workflow systems
- search and information-orientation tooling
- developer-facing structured Q&A systems

🌐 https://jamarq.digital

---

### vaexcore
Creator infrastructure and live-production tooling.

Focused on:
- streaming systems
- recording and media pipelines
- moderation and automation tooling
- highlight discovery systems
- lightweight creator-first production software

---

## Technical Focus

### Frontend
- React
- TypeScript
- Next.js
- Tailwind CSS
- Vite
- Tauri (Rust back end)
- Slint (Windows-native apps)

### Backend & Infrastructure
- Rust
- Node.js
- PHP
- REST APIs
- MySQL
- Turso / libSQL
- Cloudflare
- Vercel
- AWS
- Linux-based deployment environments

### Systems Work
- deployment workflows
- operational tooling
- media pipelines
- environment safety
- admin systems
- infrastructure debugging
- production stabilization

---

## Work

Almost everything I build lives in the [JAMARQ Digital organization](https://github.com/JAMARQ-Digital-LLC), and most of it is private: client sites and the business software behind them. The commits are mine, so my contribution graph counts them. Below is the whole of it, public or not.

### Open source

All GPL-3.0, written in Rust with Slint, for Windows.

- **[Keeplight](https://github.com/JAMARQ-Digital-LLC/keeplight)**
  Shows every light in the PC and keeps the colors you set through restarts, sleep and power loss. It drives [OpenRGB](https://openrgb.org) through its SDK server, using its own small client, and never loads OpenRGB profiles. It includes a command line and an MCP server, so any language model can operate it.

- **[Vaexil Mod Manager](https://github.com/JAMARQ-Digital-LLC/vaexil-mod-manager)**
  A multi-game mod manager. Version 1 drives the official Simple Mod Framework for HITMAN World of Assassination without changing it. Any language model can run it through its `vmm` command line and MCP server, with plan/apply, typed errors and redacted diagnostics, so no screen control is needed.

- **[Modlist Launcher](https://github.com/JAMARQ-Digital-LLC/modlist-launcher)**
  A lightweight launcher for several portable Mod Organizer 2 / Wabbajack installs. Its Steam Play button starts the modded game. It never writes to the mod installs.

- **[JAMARQ Releases](https://github.com/JAMARQ-Digital-LLC/jamarq-releases)**
  Installers and update feeds for the desktop apps. Only each app's reviewed release workflow publishes here.

### Live products

- **[JustLFG](https://justlfg.app)**
  A Discord-first bot for gaming communities: event scheduling, RSVPs and coordination across servers. It runs on Cloudflare Workers and D1, with a Premium tier billed through Stripe.

- **[Statward](https://statward.app)**
  A Destiny 2 stats bot for Discord. It reports players, Trials, clans, raids, dungeons and exotic missions from the Bungie API.

- **[vaexil.tv](https://vaexil.tv)**
  My stream site, which also hosts the game sites: [Destiny 2](https://destiny2.vaexil.tv) (Armory and an armor optimizer) and the [HITMAN map reference](https://hitman.vaexil.tv).

- **[tenra.dev](https://tenra.dev)**
  A single-piece art site: an endless, seeded descent through generated layers that never repeats.

- **[JAMARQ Digital](https://jamarq.digital)**
  The business site: websites, app and software development, and PC repair.

### Client systems

Each runs on Vercel, mostly with Next.js, Turso and R2, and has an admin the client uses day to day.

- **[Midway Music Hall](https://midwaymusichall.net)**
  Venue operations: events, a page per show and per series, seating, media and admin.

- **[Thunder Road Bar & Grill](https://trbgmidway.com)**
  Venue site and media workflow, built to stay simple to run.

- **[Midway Mobile Storage](https://midwaymobilestorage.com)**
  A container catalog with a printable booklet, communications and deployment management.

- **[Midway Town Center](https://midwaytowncenter.com)**
  A shopping center platform: storefront directory, leasing pipeline, center events and a contact inbox.

- **[Surplus Containers](https://surpluscontainers.com)**
  Public inventory and a contact form, plus an admin console for inventory imports and email campaigns.

- **[Bow Wow's Dog Spa](https://bowwowsdogspa.com)**
  A grooming business platform: booking, customer intake and media. Moved from cPanel to Next.js, Turso and R2.

- **[Midway Junk Removal](https://midway-junk-removal.com)**
  Built to turn visits into quotes: service pages, service area, FAQ and a quote form.

### Desktop software (private)

The JAMARQ suite, desktop apps in Tauri with a Rust back end:

- **Atlas**: the operator dashboard for the whole portfolio, covering pull requests and checks, sites, deploys and installed apps.
- **Scout**: finds and audits leads, then works them as deals through quotes, proposals and follow-ups.
- **Registry**: the source of truth for business records, requests, quotes and dispatch.
- **Ledger**: books, reconciled against Registry.
- **Align**: Google Business Profile operations and answer-engine visibility.
- **Assembly**: a content and document workbench with voice profiles.
- **Sentinel** and **Guardrail**: safety and policy checks across the suite.
- **Partition**: plans, simulates and lab-checks disk changes for Windows PCs, with execution locked.
- **Triage**: PC repair diagnostics, covering a bootable diagnostic drive, an open reference database and the intake app that writes the customer report.
- **Overlap**: shows the local time in each region you care about and when those regions line up.
- **Mixtape**: turns a long song list into matching Spotify and Apple Music playlists.

Vaexcore, live-production tooling for streaming:

- **Vaexcore Studio**, **Vaexcore Pulse** and **Vaexbot**: desktop apps for streaming, recording, Twitch operations, moderation and highlight discovery.
- **Vaexcore Relay**: the Cloudflare Worker that routes Twitch notifications to them.

Shared work: an agent-interface kit that gives every app the same JSON command line, plan/apply and MCP server, and website templates and kits for client builds.

---

## Engineering Posture

- Favor boring, proven tools with predictable failure modes
- Design for operational reality, not demos
- Treat deployment and data integrity as first-class concerns
- Prefer clarity over abstraction
- Verify in production-like conditions whenever possible
- Lock systems decisively once correctness is achieved

---

## Elsewhere

- JAMARQ Digital → https://jamarq.digital
- JAMARQ Digital on GitHub → https://github.com/JAMARQ-Digital-LLC
- GitHub → https://github.com/jmars319
