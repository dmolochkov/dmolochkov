## Dmitrii Molochkov

**Design Engineer** — I design products and then build them. Same hands on the Figma file and on the repository.

Dubai, UAE · [LinkedIn](https://linkedin.com/in/molochou) · [Behance](https://behance.net/milkshake1)

---

### Products

**[Pipeq](https://pipeq.app)** — team task manager · *live in production*

Kanban board for teams, built solo end-to-end. Next.js 15 · Tailwind 4 · Bun/Hono REST API · PostgreSQL 16 + Drizzle ORM, in a Bun-workspaces monorepo.

Real-time WebSocket sync, web-push notifications, optimistic UI with explicit pending and failure states, hand-written pointer-based drag & drop instead of a library, natural-language deadlines, installable PWA. Self-hosted on Docker + Caddy with one-click GitHub Actions deploy. EU hosting, GDPR export and deletion.

→ [**Case study**](https://github.com/dmolochkov/pipeq-case-study) — architecture, engineering decisions, what got reverted and why

**[Kollaba](https://kollaba.app)** — where designers and developers find each other for side projects · *released*

Next.js 16 (App Router) · React 19 · TypeScript · Tailwind 4 · Supabase — Postgres, Auth, Realtime, row-level security on every table.

GitHub and Google OAuth, real-time chat and notifications, applications and team flow, user-generated blog, image uploads through Cloudflare R2, Turnstile anti-bot, i18n infrastructure for five languages. Dark-theme design system with tokens and a component library — designed and coded by the same hand.

→ [**Case study**](https://github.com/dmolochkov/kollaba-case-study) — architecture, design system, authorization model

**Cercano** — privacy-first messenger for iOS and Android · *in development*

React Native 0.84 · TypeScript · Rust (Axum) · PostgreSQL 16 · WebRTC with a self-hosted TURN server.

Client-side AES-256 per-chat encryption, OTA JavaScript updates with binary APK patching, nine languages, separate staging and production environments with a PR-gated release flow.

→ [**Case study**](https://github.com/dmolochkov/cercano-case-study) — architecture, encryption model, native modules

> Product repositories are private — the case studies above cover the architecture and the reasoning. Happy to walk through the code itself in a call.

---

### Figma Community plugins

| Plugin | What it does |
| --- | --- |
| [Design System Audit](https://www.figma.com/community/plugin/1563463190001104520/design-system-audit) | Scans a file for color, spacing and typography violations against the design system, then fixes them one by one or in bulk |
| [TokenFlow](https://www.figma.com/community/plugin/1566384045462066800/tokenflow) | Extracts design tokens from any live website's HTML and CSS and imports them straight into Figma Variables |
| [Slide Import](https://www.figma.com/community/plugin/1646125037635586824/slide-import) | Imports PowerPoint and Google Slides decks into Figma as editable frames — client-side OOXML parsing · [source](https://github.com/dmolochkov/slide-import) |
| [FontShift](https://www.figma.com/community/plugin/1641769006791941190/fontshift) | Swaps fonts across an entire file with smart weight mapping, fully offline |
| [Font Tester](https://font-tester-ten.vercel.app) | Web app — compares the fonts installed on your own machine side by side, nothing leaves the browser |

---

### Stack

**Engineering** — TypeScript · React · Next.js · React Native / Expo · Tailwind CSS · Node.js / Bun · Hono · PostgreSQL · Drizzle ORM · Supabase · REST · WebSockets · PWA & service workers · OAuth · Figma Plugin API · Docker · Vercel · GitHub Actions

**Design** — Design systems · design tokens · component libraries · UX/UI · prototyping · user research · usability testing · accessibility · motion · brand identity · typography · Figma · Adobe Creative Suite

**Product** — Google Analytics · Amplitude · funnel and retention analysis · technical SEO
