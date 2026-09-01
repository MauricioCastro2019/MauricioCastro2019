# Mauricio Banquells Castro

**Software Engineering student · Operations-minded product builder · AI-augmented developer**

I build practical digital systems around real operational problems — especially healthcare operations, household coordination, personal workflows, content operations, and vehicle care.

My background is not a traditional software-only path. I work close to day-to-day operations, identify friction in real workflows, and use software, data, automation, and AI-assisted development to turn those problems into usable products.

## What I'm building now

### HMV Digital
Hospital operations platform developed from real workflows at Hospital Médica Vida.

Current areas include inventory and warehouse operations, purchasing, pharmacy workflows, surgery coordination, consulting-room administration, auditability, dashboards, operational knowledge, and tools for different hospital roles.

The current development line uses staged releases, PostgreSQL migrations, automated tests, role-based and object-level authorization, controlled promotion between environments, backups/rollback discipline, and post-release validation against real hospital use. Recent work has increasingly focused on release hardening and authorization boundaries rather than adding functionality by default.

**Repository:** [inventario-hospitalario-flask](https://github.com/MauricioCastro2019/inventario-hospitalario-flask)

### HogarOS
A private-alpha household operating system designed to reduce mental load and help families coordinate everyday life.

It is evolving from kitchen and inventory workflows into a broader Home Graph: people, children, pets, routines, tasks, events, spaces, objects, maintenance, household history, invitations, privacy boundaries, and contextual assistance.

The platform also explores a controlled agent/integration layer: contextual read models, explicit action confirmation, household-scoped authorization, OAuth-based access, and read-only MCP tools. The goal is not autonomous access to a family's life, but safe interfaces that can eventually let approved assistants and devices interact with household context under clear permissions.

The current product goal remains validation with a small group of real households and learning from actual use rather than adding features endlessly.

**Repository:** [HogarOS](https://github.com/MauricioCastro2019/HogarOS)

### MauOS
A personal capture-and-action layer for turning thoughts and messages into structured memory and controlled actions across my digital systems.

The first core uses a WhatsApp/Twilio adapter, Supabase-backed identity and memory, OpenAI Responses API tool calling, tasks, audit trails, and voice-note transcription. The architecture is intentionally modular while remaining a deployable monolith; channel payloads are kept outside the core contract so additional adapters can be added without coupling the agent to WhatsApp.

The current stage is an early working core, not a general autonomous assistant. Actions are risk-classified, sensitive tools remain approval-gated, and the product is being used to learn where conversational capture is genuinely more useful than another interface.

**Repository:** private (`MauOS`)

### ContenidoOS
A multi-brand content operations platform for turning observed audience signals into structured decisions, conversations, publishing workflows, and learning.

It now includes brand-scoped Campaigns, Studio and Calendar workflows, manual-first Publishing, evidence-gated Analytics/Learnings, authenticated multi-brand workspaces, Community and Connections modules, and a server-side Meta/Instagram integration. The system deliberately separates simulated, observed, and confirmed evidence instead of presenting generated metrics as real performance.

The current goal is to prove the complete operating loop with real brands and content before expanding automation or adding more channels.

**Repository:** private (`ContenidoOS`)

### Mi Auto Pro — The Garage
A vehicle-first product for preserving the complete memory of a car: maintenance, repairs, documents, expenses, recurring issues, alerts, and care history.

The first alpha grew from a real vehicle case and is being developed in an isolated preview environment before any production integration.

**Repository:** [realg4wash-os](https://github.com/MauricioCastro2019/realg4wash-os)

## How I work

I use AI extensively as part of my development workflow — for exploration, implementation, testing, documentation, debugging, architecture review, adversarial review, and product iteration.

I don't present AI-assisted work as something it isn't. My responsibility is to define the problem, provide real operational context, choose boundaries and tradeoffs, validate generated changes, test behavior, review failures, document decisions, and decide what is safe and useful enough to ship.

Increasingly, I use different AI-assisted passes for implementation, review, red-teaming, and release control rather than treating one generated answer as authoritative. AI increases my execution speed and breadth; it does not replace product judgment, operational ownership, verification, or responsibility for the result.

I care more about whether a system works in the real world than about pretending every line was written manually.

## Current stack

- Python / Flask
- TypeScript / React / Next.js
- PostgreSQL / SQLite
- Supabase
- HTML / CSS / JavaScript
- Git / GitHub
- GitHub Actions
- Vercel / Railway / Render
- Alembic migrations
- OAuth / JWT authorization patterns
- Webhooks and external API integrations
- OpenAI Responses API and tool calling
- Twilio / WhatsApp integrations
- Model Context Protocol (MCP)
- AI-assisted engineering and review workflows

## What I'm learning

I'm currently studying **Software Engineering / Software Development** while building systems from real operational use cases.

My current learning focus includes:

- database design, migrations, and data integrity;
- product and integration architecture;
- testing, CI, staged releases, backups, rollback, and deployment safety;
- privacy, object-level authorization, and multi-tenant systems;
- OAuth, webhooks, external APIs, MCP, and agent-facing interfaces;
- tool schemas, approval boundaries, auditability, and safe agent actions;
- observability and operational data;
- designing software that non-technical users can actually use;
- separating generated hypotheses from observed evidence;
- deciding when not to automate or expand a system yet.

## What drives me

I like turning messy, everyday problems into clear systems.

Healthcare, a home, personal workflows, content operations, or a car may look like completely different domains, but the pattern is often the same: information is fragmented, important history lives in people's heads, workflows depend on memory, and decisions are made without enough data.

I want to build tools that make those environments calmer, more understandable, and easier to operate.

---

**Building in public where it makes sense. Learning fast. Using AI openly. Trying to make the software genuinely useful.**
