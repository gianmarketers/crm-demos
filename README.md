# CRM Portfolio Projects

Client-facing demo apps and portfolio assets for a freelance HubSpot / CRM specialist.

**🌐 Live site:** https://gianmarketers.github.io/crm-demos/

## What's here

| Path | What it is |
|---|---|
| [`index.html`](index.html) | **Portfolio Hub** — the landing page served at the live URL above. Hero with an animated portal-health card, service areas, a live-demos section linking to both demos below, representative results, process and a contact CTA. |
| [`crm-migration-studio/index.html`](crm-migration-studio/index.html) | **CRM Migration Studio** — an interactive, client-facing demo of a full CRM migration engagement. Single self-contained HTML file, no dependencies, no build step. |
| [`hubspot-audit-demo/index.html`](hubspot-audit-demo/index.html) | **Audit Studio** — an interactive sample HubSpot portal audit across **three selectable sample portals** (mid-market, agency, enterprise), each with its own full audit: 8 scored areas, ~30 findings with impact + fix, an impact/effort fix plan, fixed pricing tiers and an FAQ. HubSpot-only. Same single-file format. |
| [`gohighlevel-demo/index.html`](gohighlevel-demo/index.html) | **GoHighLevel Client Demo — Med Spa** (Radiance Aesthetics). Interactive sub-account mock: dashboard, pipeline, unified conversations, calendar, automation/workflow builder, funnels, reputation, reporting + guided tour. Ships with [`cover.png`](gohighlevel-demo/cover.png). The base template for the niche variants below. |
| [`gohighlevel-home-services/index.html`](gohighlevel-home-services/index.html) | **GoHighLevel Client Demo — Home Services** (Summit Home Services · HVAC/plumbing/electrical). Same engine, fully reskinned: jobs pipeline, trade automations (missed-call text-back, quote follow-up, seasonal maintenance), LSA lead sources. Ships with [`cover.png`](gohighlevel-home-services/cover.png). |
| [`gohighlevel-real-estate/index.html`](gohighlevel-real-estate/index.html) | **GoHighLevel Client Demo — Real Estate** (Coastline Realty). 6-stage deal pipeline (New Lead → Closed), GCI reporting, real-estate automations (speed-to-lead, long-term buyer nurture, past-client/SOI), Zillow/FB lead sources. Ships with [`cover.png`](gohighlevel-real-estate/cover.png). |
| [`gohighlevel-dental/index.html`](gohighlevel-dental/index.html) | **GoHighLevel Client Demo — Dental/Ortho** (Bright Smile Dental). New-patient pipeline (→ Case Accepted), production & case-acceptance KPIs, dental automations (missed-call text-back, recall/reactivation, treatment-plan follow-up). Ships with [`cover.png`](gohighlevel-dental/cover.png). |
| [`docs/PORTFOLIO_PLAYBOOK.md`](docs/PORTFOLIO_PLAYBOOK.md) | Project roadmap for both Upwork accounts, how to present the demo, and a complete Fiverr launch plan. |

## CRM Migration Studio

A six-step walkthrough of a real migration process, run on synthetic data:

1. **Scope** — pick any source (Zoho, GoHighLevel, Pipedrive, Salesforce, CSV) and destination (HubSpot, GoHighLevel, Zoho)
2. **Connect** — simulated OAuth with least-privilege scopes and pre-flight checks
3. **Field mapping** — auto-matching with per-field decisions, custom-field creation, transforms (name splitting, read-only date handling), and pipeline **stage mapping**
4. **Data quality** — dry-run scan that surfaces duplicates, invalid emails, missing owners, phone-format drift, orphaned deals; each with an approvable fix strategy
5. **Migration** — animated batched run with a live log, throughput and verification
6. **Report** — KPI tiles, records-by-object chart, issue-resolution summary, downloadable sample report, and a booking CTA

Also includes a **guided tour**, light/dark theme, and full mobile support.

### Customize it (2 minutes)

Open `crm-migration-studio/index.html` and edit the `CONFIG` block at the top
of the `<script>` section — your name, title, CTA label and booking link.

### Host it (free options)

- **Netlify Drop** — drag the `crm-migration-studio` folder onto [app.netlify.com/drop](https://app.netlify.com/drop). Live URL in ~10 seconds.
- **GitHub Pages** — enable Pages on this repo (Settings → Pages → deploy from branch), then link `/crm-migration-studio/`.
- **Vercel** — `vercel deploy` from the folder.

The file is fully self-contained (no CDNs, no fonts, no images), so it also
works attached to an email or opened from a USB stick.

> All data in the demo is synthetic. Nothing connects to a live system.

## Audit Studio (HubSpot)

A five-step interactive sample audit — HubSpot only. The prospect picks one of
**three sample portals**, each a different real-world story with its own complete,
hand-written audit:

- **Acme Robotics** — the typical mid-market drift (health 59/100)
- **Brightlane Media** — a fast-growing agency, marketing ahead of sales ops (69/100)
- **Northwind SaaS** — enterprise sprawl, five years of nobody-turned-anything-off (44/100)

Each audit runs the same process:

1. **Portal** — pick the portal; see its size, tiers and the 8-area checklist
2. **Scan** — animated read-only scan across the eight areas
3. **Findings** — health-score ring, revenue-at-risk and quick-win stats, severity filters, category jump chips, expand-all, and ~30 findings each written as *symptom → why it costs money → the fix* (data quality, pipeline, automation, email/deliverability, sales adoption, reporting/attribution, integrations, governance)
4. **Fix plan** — the findings ranked into a top-10 list with an impact-vs-effort matrix and a 30-day roadmap
5. **Your audit** — process, deliverables, **fixed pricing tiers**, an FAQ accordion, read-only access reassurance, a booking CTA, and a downloadable per-portal sample report

Also includes the **guided tour**, light/dark theme, mobile support, and an
"audit a different portal" flow so a prospect can compare all three.

Customize the same way — edit the `CONFIG` and `PRICING` blocks at the top of the
`<script>` section. Host it exactly like the Migration Studio (drag
`hubspot-audit-demo` onto Netlify Drop, or GitHub Pages / Vercel).

> All portals and numbers are synthetic. Not affiliated with HubSpot, Inc.
