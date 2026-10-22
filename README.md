# Duong Dinh Manh (RumikaRin)

Software Engineer based in Hanoi, Vietnam. Focused on full-stack web platforms, AI infrastructure gateways, and deterministic procedural graphics.

[GitHub](https://github.com/RumikaRin) &nbsp;·&nbsp; [Email](mailto:duongdinhmanh002@gmail.com)

---

## Selected Systems & Projects

### [Maison de FLOF](https://github.com/RumikaRin/Maison-de-FLOF)
*Atelier paint e-commerce platform and interactive color visualizer.*

- **Stack:** Next.js 15 (App Router), React 19, Tailwind CSS, Prisma 6, Neon PostgreSQL, Upstash Redis.
- **Architecture & Security:** Zero-Style CSP enforced at Edge Middleware (per-request cryptographic nonces, disallowing inline styles and `unsafe-eval`). RFC 6238 TOTP MFA with AES-256-GCM secret encryption, Scrypt backup codes, and anti-replay timesteps.
- **Data & Transactions:** Concurrency-safe inventory ledgers with deterministic SKU lock ordering; transactional outbox pattern for asynchronous email notifications.
- **Verification:** 344 unit and contract tests, Playwright end-to-end browser suites, 100/100 gstack automated QA health score.

---

### [Gemini Web Adapter](https://github.com/RumikaRin/gemini-web-adapter)
*Reverse-proxy AI gateway transforming browser sessions into OpenAI-compatible endpoints.*

- **Stack:** Node.js, Express, Google `batchexecute` RPC engine.
- **Protocol Bridge:** Decodes internal Google RPC protocols (`SNlM0e`), exposing standard `/v1/models` and `/v1/chat/completions` REST endpoints.
- **Resilience:** Multi-account session cookie pooling, automatic failover on HTTP 429 rate limits, and tool-calling adapter for CLI agents (Claude Code, OpenCode).

---

### [Motion Studio](https://github.com/RumikaRin/VideoStudio)
*Deterministic procedural 2D animation and video generation engine.*

- **Stack:** JavaScript, HTML5 Canvas, GSAP, Python (audio DSP).
- **Pure-Function Rendering:** Implements `window.seek(t)` to paint exact frames deterministically for any timestamp `t`.
- **Pipeline:** Spring physics kinetics, multi-aspect-ratio viewport scaling, and headless subframe capture for programmatic MP4 rendering.

---

### [Crimson Garden](https://github.com/RumikaRin/CrimsonGarden)
*Interactive learning and adaptive assessment platform.*

- **Stack:** Next.js 15, React 19, TypeScript, Radix UI, TanStack Query, Prisma ORM, PixiJS.
- **Interactive 3D:** Real-time 3D interactive canvases powered by Spline (`@splinetool/react-spline`) with 2D rendering optimizations and Vitest test coverage.

---

### [FinGlow](https://github.com/RumikaRin/FinGLow)
*Personal wealth and expense management application.*

- **Stack:** Flutter, Dart, Supabase.
- **Architecture:** Local-first data architecture prioritizing offline storage and user privacy, with optional encrypted cloud synchronization.

---

### [Aurora Hotel](https://github.com/RumikaRin/AuroraHotel)
*Hospitality booking system with automated verification suites.*

- **Stack:** Next.js, TypeScript, Tailwind CSS, Playwright.
- **Verification:** Design token conformance checks, dynamic pricing engines, automated database state fixtures, and end-to-end integration tests.

---

## Technical Focus

- **Languages:** TypeScript, JavaScript (Node.js), Dart, Python, SQL
- **Web & UI Platforms:** Next.js 15 (App Router, Server Components, Server Actions), React 19, Tailwind CSS, Flutter, Spline 3D, PixiJS
- **Backend & Data Stores:** PostgreSQL, Prisma ORM, Neon Serverless, Redis (Upstash), Supabase
- **Security & Infrastructure:** Content Security Policy (strict nonces, zero inline styles), Auth.js v5, RFC 6238 TOTP 2FA, Transactional Outbox, Reverse Proxies & RPC Translation, Docker, GitHub Actions CI/CD
- **Testing & Quality Assurance:** Vitest, Playwright E2E, Contract Testing (OpenAPI 3.1), WCAG 2.1 AA Contrast Audits

---

## GitHub Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=RumikaRin&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="RumikaRin's GitHub stats" height="155" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RumikaRin&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" height="155" />
</div>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=RumikaRin&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" />
</p>

---

<div align="center">
  <sub>Duong Dinh Manh &nbsp;·&nbsp; Hanoi, Vietnam</sub>
</div>
