<h1 align="center">Murat Sert</h1>

<p align="center">
  Product engineer building trustworthy AI automation, open-source tooling, and self-hosted systems.<br>
  Founder of <a href="https://kelyvaro.com"><b>Kelyvaro</b></a> — from first prototype to production.
  <br><sub>Karlsruhe · Türkçe / Deutsch / English</sub>
</p>

---

### Current focus

I am building **[NEXORA](https://github.com/msertdev/nexora)**, an Apache-2.0
self-hosted workspace for projects, issues, and team delivery. It combines a
Next.js 16 web app, a NestJS API, PostgreSQL and Prisma in a TypeScript monorepo,
with Docker Compose and Caddy for deployment. The next milestone is **NEXORA AI
Agent v1**.

I also build **[Kelyvaro](https://kelyvaro.com)**, a live product that helps
people in Turkey apply directly to German employers. It matches openings from
employer career sites, prepares a German CV and cover letter for each role, and
sends only after the user approves the application.

### Selected work

| Project | What it is | Evidence |
|---|---|---|
| **[NEXORA](https://github.com/msertdev/nexora)** | Self-hosted project and team management platform with role-based organizations, issue tracking, email verification, and invitations | [Source](https://github.com/msertdev/nexora) · [CI](https://github.com/msertdev/nexora/actions/workflows/continuous-integration.yml) · [Security policy](https://github.com/msertdev/nexora/security/policy) |
| **[grounded-json](https://github.com/msertdev/grounded-json)** | TypeScript CLI and SDK for schema-valid local web extraction with field-level evidence and deterministic offline replay | [Source](https://github.com/msertdev/grounded-json) · [npm](https://www.npmjs.com/package/grounded-json) |
| **[Kelyvaro](https://github.com/msertdev/kelyvaro-showcase)** | Public product showcase for a live, Germany-focused job-application workflow; production source remains private | [Live product](https://kelyvaro.com) · [Case study](https://github.com/msertdev/kelyvaro-showcase) |
| **[ats-boards](https://github.com/msertdev/ats-boards)** | Dependency-free TypeScript library and CLI that discovers and normalizes public German employer job boards across 12 ATS providers | [Source](https://github.com/msertdev/ats-boards) · [npm](https://www.npmjs.com/package/ats-boards) |

### Engineering principles

- **Evidence before confidence.** Structured extraction includes source
  evidence and deterministic replay; unsupported values do not silently enter
  strict results.
- **Consent is an architectural boundary.** Kelyvaro's public case study
  documents explicit approval before sending, consent-gated analytics, and
  row-level security for application data.
- **Security belongs in the default path.** NEXORA uses database-backed
  sessions, server-enforced roles, origin validation, protected CI, CodeQL, and
  secret scanning.
- **Failures stay explicit.** Public integrations distinguish empty results
  from access, rate-limit, permission, and format failures.
- **Measurements keep their limits.** Experimental work such as
  [keepwatching](https://github.com/msertdev/keepwatching) publishes sample
  sizes and leaves untested findings visibly untested.

### Stack

`TypeScript` · `Next.js` · `React` · `NestJS` · `Node.js` · `PostgreSQL` ·
`Prisma` · `Docker` · `Playwright` · `Tailwind CSS` · `GitHub Actions`

### Contact

<p>
  <a href="https://kelyvaro.com">Website</a> ·
  <a href="https://www.linkedin.com/in/kelyvaro/">LinkedIn</a> ·
  <a href="mailto:info@kelyvaro.com">Email</a>
</p>
