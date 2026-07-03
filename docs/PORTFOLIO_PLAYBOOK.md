# Portfolio Playbook — What to Build, Where to Post It, and the Fiverr Launch

*For a freelancer running two Upwork accounts (HubSpot-focused + GoHighLevel-focused)
with Zoho expertise, planning a Fiverr expansion.*

---

## 1. Where you stand

- **HubSpot account** — deep history, many projects. Credibility is established; what wins here now is *specialization signals* (migrations, integrations, RevOps) that justify higher rates.
- **GoHighLevel account** — thin history but one flagship: the full client demo app. One strong interactive asset already outperforms a list of small gigs; it needs siblings, not replacements.
- **Zoho** — claimed in your profile but not yet *shown* anywhere. An unproven claim on a profile is a weak signal; one demo fixes it.
- **The gap nobody's asset covers:** work that spans CRMs. Migration and integration jobs are consistently among the highest-budget CRM listings, and they're exactly where a "I know all three platforms" freelancer beats a single-platform specialist.

That gap is why the first build is the **CRM Migration Studio** (in this repo).

---

## 2. The build: CRM Migration Studio

**What it is:** an interactive, client-facing walkthrough of a real migration
engagement — scope → connect → field mapping → dry run → migration → report —
on synthetic data. Same "send it before they hire you" play as your GHL demo app.

**Why this project, specifically:**

1. **It works on BOTH Upwork accounts.** On the HubSpot account: "watch a Zoho/Pipedrive/GHL → HubSpot migration before you buy." On the GHL account: "watch me move your agency's data INTO GoHighLevel." Same file, two framings — the source/destination picker does the repositioning for you.
2. **Migration buyers are terrified of data loss.** The demo directly answers the fear: field coverage meter, explicit fix strategies, verification step, rollback snapshot. It sells trust, not features.
3. **It demonstrates cross-CRM fluency without saying so.** Object names change per platform (Accounts → Companies, Opportunities → Deals), stage mapping shows real pipelines, and the mapping table shows real API property names (`hubspot_owner_id`, `Mailing_Street`, `pipelineStageId`). Practitioners recognize practitioners.
4. **It productizes into a Fiverr gig** (§5) — migration is one of the few CRM services with clean Basic/Standard/Premium tiers.

**Before you post it:**
- [ ] Edit the `CONFIG` block (name, title, CTA link → your Upwork profile or Calendly)
- [ ] Host it (Netlify Drop is fastest — see README)
- [ ] Record a 60–90s Loom driving through it (thumbnail + link in the portfolio entry)

**Portfolio entry template (Upwork):**
> **Title:** Interactive CRM Migration Demo — Zoho/GHL/Salesforce → HubSpot with zero data loss
> **Description:** A live, clickable walkthrough of my migration process: automated field mapping with human review, a dry-run data-quality scan (duplicates, invalid emails, orphaned deals), pipeline stage mapping, and a verified hand-off report. Built from the process I run on real engagements. *Click through it yourself — takes 2 minutes.*
> **Skills:** CRM Migration, HubSpot, Zoho CRM, GoHighLevel, Data Cleansing, API Integration

**Proposal snippet (paste into migration-job proposals):**
> Before you decide, click through this 2-minute interactive demo of exactly how I run migrations — including how I handle duplicates, bad emails and pipeline stages: **[link]**. It's the same process I'd run on your ~X,XXX records.

---

## 3. Next builds, ranked

Ordered by (impact on winning jobs) ÷ (effort). Build top-down.

### 3.1 CRM Audit / Health-Check Report *(next up — pairs with a lead-gen tactic)*
An interactive "CRM health report" for a fictional company: lead-response-time, pipeline hygiene (stale deals, skipped stages), automation coverage, data quality score, with a prioritized fix list. **Why:** "free audit" is the highest-converting cold offer in CRM freelancing; this demo shows the deliverable before you've done a minute of work. Works on both accounts, and becomes a $50–150 Fiverr gig with near-zero marginal effort per order.

### 3.2 Zoho showcase — "Zoho Automation Pack" demo
You claim Zoho; nothing proves it. A compact demo of 5–6 real Deluge automations (lead assignment round-robin, SLA escalation, quote approval chain, client portal touch) presented in the same interactive style. **Why:** Zoho jobs have noticeably less freelancer competition than HubSpot jobs; even a modest showcase puts you in a thinner pool.

### 3.3 GHL Snapshot storefront — industry funnel demos
2–3 niche demos (e.g., med spa, roofing, real estate): pipeline, calendar, SMS/email follow-up sequences, reactivation campaign — presented like your existing GHL app. **Why:** GHL buyers are agencies and local-niche operators who buy *outcomes for their niche*, and snapshots are a sellable product (one build, many sales). Feeds a Fiverr gig directly.

### 3.4 HubSpot developer mini-library
3–4 custom-coded workflow actions / a CRM card (e.g., "format & validate phone in workflow", "deal-desk approval card") in a public repo with clean READMEs. **Why:** targets the top of the HubSpot rate range (Operations Hub / developer work), where portfolios are code, not screenshots.

### 3.5 Cross-CRM integration demo ("CRM ⇆ anything sync")
Interactive demo of a two-way sync design: field ownership rules, conflict resolution, retry/queue behavior. **Why:** integration retainers are recurring revenue, but the buyer pool is smaller than migration — hence ranked last despite high job values.

---

## 4. Presenting on the two Upwork accounts

**HubSpot account** — position as *"HubSpot specialist who can bring your data in from anywhere."*
- Portfolio order: Migration Studio → best HubSpot client projects → (later) audit demo, dev mini-library.
- Add a **Project Catalog** listing: "CRM → HubSpot migration, done-for-you" with 3 tiers mirroring §5's gig pricing. Catalog listings get search placement proposals don't.

**GoHighLevel account** — position as *"the GHL builder who shows you the product before you pay."*
- Portfolio order: your existing GHL client app → Migration Studio (framed as "move your clients INTO GHL") → snapshot demos as they're built.
- With only one review-generating project, the interactive demos ARE the social proof — lead every proposal with a link.

**Rule for both:** every portfolio item gets (a) a live link, (b) a Loom, (c) one line about a business result, real or clearly-labeled-representative. Never post a demo pretending it's client work — "interactive demo I built to show my process" reads as *more* impressive, not less.

---

## 5. Fiverr launch plan

**What I can't do:** create the account itself — Fiverr signup needs your identity,
phone verification, and (in most regions) ID. That part is ~20 minutes of your time.
Everything below is ready to paste once you're in.

### 5.1 Account setup checklist
- [ ] Sign up as a **seller**, same professional identity/photo as Upwork (cross-platform consistency builds trust; note that *reviews* don't transfer, so your gig images must carry the proof)
- [ ] Seller profile: lead with the three platforms in the first line; link nothing external (Fiverr forbids off-platform links — your demos go in as **gig videos/PDFs**, not URLs)
- [ ] Take the relevant Fiverr skill tests if offered for your category
- [ ] Set up **Requirements** on every gig (§5.5) — it filters bad buyers automatically

### 5.2 Gig 1 — CRM Migration *(the Migration Studio productized)*
**Title:** *I will migrate your CRM data to HubSpot, GoHighLevel or Zoho with zero data loss*

| | Basic — $195 | Standard — $495 | Premium — $1,250 |
|---|---|---|---|
| Scope | Up to 2,000 contacts, 1 object | Up to 10,000 records, contacts + companies + deals | Up to 50,000 records, all objects + notes/activities |
| Field mapping | Standard fields | + custom fields | + custom objects & transforms |
| Data quality | Dedupe report | Dedupe + cleanup applied | Full dry run + fix strategies + verification report |
| Extras | — | Pipeline stage mapping | Automation rebuild (up to 5 workflows), 2-week support |
| Delivery | 4 days | 7 days | 14 days |

**Gig video:** screen recording of the Migration Studio with a voiceover — this is exactly what gig videos are for, and almost no competitor will have one.

### 5.3 Gig 2 — CRM Audit
**Title:** *I will audit your HubSpot, GoHighLevel or Zoho CRM and deliver a prioritized fix plan*
Basic $75 (video audit, 15-point checklist) / Standard $175 (written report + fix list) / Premium $395 (report + top-3 fixes implemented). **Purpose:** cheap entry point that generates reviews fast and upsells into Gig 1 and Gig 3.

### 5.4 Gig 3 — GoHighLevel build
**Title:** *I will build your GoHighLevel account: funnels, pipelines, automations and snapshots*
Basic $150 (1 funnel + pipeline) / Standard $450 (full sub-account setup) / Premium $950 (agency snapshot, white-label, training video). Reuses everything from your GHL flagship app.

### 5.5 Requirements form (all gigs)
1. Which CRM are you moving **from** and **to** (or auditing)? 2. Roughly how many contacts/records? 3. Admin access available, or should I work from an export? 4. Any custom fields, integrations or automations I should know about? 5. Deadline or cut-over date?

### 5.6 Fiverr vs Upwork positioning
Upwork = custom scoped engagements, higher ceilings, proposals. Fiverr = productized fixed-scope packages, search-driven, reviews compound. **Don't clone your Upwork profile text** — write Fiverr copy around the package ("what you get in 7 days"), not around yourself.

---

## 6. First 30 days

| When | Do |
|---|---|
| Week 1 | Customize + host Migration Studio · record Loom · add to both Upwork portfolios · create Fiverr account |
| Week 2 | Publish Fiverr Gigs 1–2 with the demo video · add Upwork Project Catalog migration listing · start using the proposal snippet on every migration job |
| Week 3 | Build the CRM Audit demo (next repo project) · publish Gig 3 |
| Week 4 | Build the Zoho Automation Pack demo · review which proposals with the demo link got replies vs without — double down on what moved |
