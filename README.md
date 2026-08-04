## Dmitrii Molochkov

**Design Engineer.** I design products and then build them. Same hands on the Figma file and on the repository.

Dubai, UAE · [LinkedIn](https://linkedin.com/in/molochou) · [Behance](https://behance.net/milkshake1)

---

### Products

**[Pipeq](https://pipeq.app)** · team task manager · *live in production*

Kanban board for teams, built solo end to end. Next.js 15, Tailwind 4, a Bun/Hono REST API and PostgreSQL 16 with Drizzle ORM, in a Bun-workspaces monorepo.

Real-time WebSocket sync, web-push notifications, optimistic UI with explicit pending and failure states, hand-written pointer-based drag and drop instead of a library, natural-language deadlines, installable PWA. Self-hosted on Docker and Caddy with one-click GitHub Actions deploy. EU hosting, GDPR export and deletion.

[**Case study**](https://github.com/dmolochkov/pipeq-case-study): architecture, engineering decisions, and what got reverted.

**[Kollaba](https://kollaba.app)** · where designers and developers find each other for side projects · *released*

Next.js 16 (App Router), React 19, TypeScript and Tailwind 4 on Supabase, with Postgres, Auth, Realtime and row-level security on every table.

GitHub and Google OAuth, real-time chat and notifications, applications and team flow, user-generated blog, image uploads through Cloudflare R2, Turnstile anti-bot, i18n infrastructure for five languages. Dark-theme design system with tokens and a component library, designed and coded by the same hand.

[**Case study**](https://github.com/dmolochkov/kollaba-case-study): architecture, design system, authorization model.

**Cercano** · privacy-first messenger for iOS and Android · *in development*

React Native 0.84 and TypeScript against a Rust (Axum) backend, PostgreSQL 16, WebRTC with a self-hosted TURN server.

Client-side AES-256 per-chat encryption, OTA JavaScript updates with binary APK patching, nine languages, separate staging and production environments with a PR-gated release flow.

[**Case study**](https://github.com/dmolochkov/cercano-case-study): architecture, encryption model, the migration off Flutter.

> Product repositories are private. The case studies above cover the architecture and the reasoning, and I'm happy to walk through the code itself in a call.

---

### Figma Community plugins

| Plugin | What it does |
| --- | --- |
| [Design System Audit](https://www.figma.com/community/plugin/1563463190001104520/design-system-audit) | Scans a file for color, spacing and typography violations against the design system, then fixes them one by one or in bulk |
| [TokenFlow](https://www.figma.com/community/plugin/1566384045462066800/tokenflow) | Extracts design tokens from any live website's HTML and CSS and imports them straight into Figma Variables |
| [Slide Import](https://www.figma.com/community/plugin/1646125037635586824/slide-import) | Imports PowerPoint and Google Slides decks into Figma as editable frames, parsing OOXML in the browser. [Source](https://github.com/dmolochkov/slide-import) |
| [FontShift](https://www.figma.com/community/plugin/1641769006791941190/fontshift) | Swaps fonts across an entire file with smart weight mapping, fully offline |
| [Font Tester](https://font-tester-ten.vercel.app) | Web app that compares the fonts installed on your own machine side by side. Nothing leaves the browser |

---

### Stack

**Engineering.** TypeScript, React, Next.js, React Native / Expo, Flutter, Tailwind CSS, Node.js / Bun, Hono, PostgreSQL, Drizzle ORM, Supabase, REST, WebSockets, PWA and service workers, OAuth, Figma Plugin API, Docker, Vercel, GitHub Actions.

**Design.** Design systems, design tokens, component libraries, UX/UI, prototyping, user research, usability testing, accessibility, motion, brand identity, typography, Figma, Adobe Creative Suite.

**Product.** Google Analytics, Amplitude, funnel and retention analysis, technical SEO.
