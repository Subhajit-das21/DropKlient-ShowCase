<div align="center">

<img src="assets/logo.svg" alt="dropklient logo" width="64" height="64" />

# dropklient

**The client portal built for freelancers**

[dropklient.com](https://dropklient.com) — live and in production

[![Live](https://img.shields.io/badge/status-live-22c55e)](https://dropklient.com)
[![Built with Astro](https://img.shields.io/badge/built%20with-astro-FF5D01)](https://astro.build)

</div>

---

## What it is

Most freelancers manage client work across five different tools — email for briefs, WhatsApp for quick questions, Google Drive for files, and a separate thread somewhere for feedback and approvals. dropklient replaces all of that with one link per project. The client opens it, no account required, and everything — the brief, the files, the feedback, the deliverables — lives in one organized place.

Built for freelance developers, designers, video editors, writers, and small agencies who are tired of chasing client replies across six different apps.

---

## See it

<div align="center">
  <!-- TODO: add real dashboard screenshot before going live (assets/screenshots/dashboard.png) -->
  <p><em>The freelancer dashboard — every active project, at a glance.</em></p>
</div>

<div align="center">
  <!-- TODO: add real portal screenshot before going live (assets/screenshots/portal.png) -->
  <p><em>What the client sees — no login, just the link.</em></p>
</div>

---

## The problem

Freelancers lose hours every week to client communication that has no structure: vague briefs that need three follow-up emails, files buried in a Drive folder nobody can find, feedback scattered across WhatsApp and email with no record of what was actually approved. None of that is the work — it's the overhead around the work.

dropklient exists to remove that overhead, not add another tool to the pile.

---

## Core features

**Client portals, no account required**
Each project gets a unique link. Clients access it directly — no sign-up, no password, nothing to forget.

**Structured intake**
Customizable brief forms with required/optional fields and file attachments, so the first conversation with a client is useful instead of a blank email.

**Files, organized**
Uploads with automatic version history (no silent overwrites) and folder organization for larger projects.

**Feedback that doesn't disappear**
Threaded discussions with resolution tracking — every piece of feedback has a permanent home, not a buried message in a chat app.

**Approvals with a record**
Clients approve or request changes on deliverables directly. Every decision is timestamped and attributable.

**Built-in notifications**
Both the freelancer and the client (if they opt in) get notified by email when something happens — a brief is submitted, work is uploaded, a milestone is hit.

**Payments without picking sides**
Razorpay for India, Lemon Squeezy for everywhere else — clients pay the way that's natural for their country, automatically.

---

## Tech stack

| | |
|---|---|
| **Framework** | [AstroJS](https://astro.build) — server-rendered by default, ships minimal JS |
| **Styling** | [Tailwind CSS v4](https://tailwindcss.com) — custom design tokens, no default theme |
| **Hosting** | [Cloudflare Pages](https://pages.cloudflare.com) — edge deployment, global latency |
| **Database** | [Cloudflare D1](https://developers.cloudflare.com/d1/) — SQLite at the edge |
| **File storage** | [Cloudflare R2](https://developers.cloudflare.com/r2/) — S3-compatible, zero egress fees |
| **Auth** | [Lucia](https://lucia-auth.com) — session-based, no third-party auth dependency |
| **Email** | [Resend](https://resend.com) — transactional delivery |
| **Payments** | Razorpay + Lemon Squeezy — dual gateway for India and international customers |

---

## About this repository

**This is a showcase repository, not the production source code.**

dropklient's actual codebase is private — standard for a commercial product handling real customer data, payments, and business logic. This repo exists to present the product publicly: the README you're reading, visual references, and an honest look at how it's built, without exposing the implementation details, infrastructure configuration, or anything that would let someone clone and run a copy of the live service.

If you're evaluating this as a portfolio piece or want to talk about how something specific was built, reach out — see below.

---

## Try it

dropklient is live and accepting new users.

**[→ dropklient.com](https://dropklient.com)**

---

## About the founder

dropklient is built and run by **Subhajit (SJ)** — solo founder, end-to-end: product, design, engineering, infrastructure, and support.

- Website: [shubhajitdas.in](https://shubhajitdas.in)
- Email: [hello@shubhajitdas.in](mailto:hello@shubhajitdas.in)

---

<div align="center">
<sub>© 2026 dropklient. All rights reserved.</sub>
</div>
