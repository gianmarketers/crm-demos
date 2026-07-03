# CRM Portfolio Projects

Client-facing demo apps and portfolio assets for a freelance CRM specialist
(HubSpot · GoHighLevel · Zoho CRM).

## What's here

| Path | What it is |
|---|---|
| [`crm-migration-studio/index.html`](crm-migration-studio/index.html) | **CRM Migration Studio** — an interactive, client-facing demo of a full CRM migration engagement. Single self-contained HTML file, no dependencies, no build step. |
| [`hubspot-audit-demo/index.html`](hubspot-audit-demo/index.html) | **Audit Studio** — an interactive sample HubSpot portal audit: 8 scored areas, 33 checks, expandable findings with impact + fix, an impact/effort fix plan, and the engagement deliverables. HubSpot-only. Same single-file format. |
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
