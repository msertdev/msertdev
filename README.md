<h1 align="center">Murat Sert</h1>

<p align="center">
  Product engineer building trustworthy AI automation and data systems.<br>
  Founder of <a href="https://kelyvaro.com"><b>Kelyvaro</b></a> — from first prototype to production.
  <br><sub>Karlsruhe · Türkçe / Deutsch / English</sub>
</p>

---

### What I build

I turn operational problems into products: finding and normalising data from
unreliable external systems, generating documents without inventing facts, and
shipping the result with clear consent and failure boundaries.

**Current focus:** [Kelyvaro](https://kelyvaro.com), a live product that helps
people in Turkey apply directly to German employers. It matches openings from
employer career sites, prepares a German CV and cover letter for each role, and
sends only after the user approves the application.

### Selected work

| Project | Problem | What I own | Proof |
|---|---|---|---|
| **[Kelyvaro](https://github.com/msertdev/kelyvaro-showcase)** | A careful German application takes too long and is easy to get wrong | Product and engineering: matching, fact-checked generation, consent, data model and design system | [Live product](https://kelyvaro.com) · [case study](https://github.com/msertdev/kelyvaro-showcase) |
| **[ats-boards](https://github.com/msertdev/ats-boards)** | German employers publish jobs through incompatible ATS providers | A dependency-free TypeScript library and CLI that discovers and normalises public boards from 12 providers | [Source](https://github.com/msertdev/ats-boards) · [npm](https://www.npmjs.com/package/ats-boards) |
| **[keepwatching](https://github.com/msertdev/keepwatching)** | Short-form format advice often presents guesses as measured facts | A deterministic renderer and evidence model that keeps hypotheses, samples and content effects separate | [Source](https://github.com/msertdev/keepwatching) · [live gallery](https://msertdev.github.io/keepwatching) |

### Engineering decisions I care about

- **Facts stay outside the model.** Generated CV claims are checked against the
  user's profile; prompt changes have regression tests.
- **Public integrations fail explicitly.** ATS results distinguish an empty
  board from access, rate-limit and format failures.
- **Consent is part of the architecture.** Applications require user approval;
  analytics are consent-gated; database tables use row-level security.
- **Evidence keeps its sample size.** `keepwatching` publishes untested formats
  as untested and runs its date reader in four time zones.

### Stack

`TypeScript` · `Next.js` · `React` · `Node.js` · `Postgres / Supabase` ·
`Playwright` · `Tailwind CSS` · `Vercel` · `Remotion`

### Contact

<p>
  <a href="https://kelyvaro.com">Website</a> ·
  <a href="https://www.linkedin.com/in/kelyvaro/">LinkedIn</a> ·
  <a href="mailto:info@kelyvaro.com">Email</a>
</p>
