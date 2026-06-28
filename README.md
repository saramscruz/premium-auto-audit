# Premium Automotive Digital Audit — Portugal 2026

A structured comparative analysis of digital purchase funnels across five premium automotive brands in the Portuguese market: Mercedes-Benz, BMW, Audi, Volvo, and Porsche.

## What this is

This audit maps the gap between measurable digital demand and live conversion readiness across five brands in one market. As of 27/06/2026, no brand in this comparison has activated online purchase in Portugal. The analysis identifies where the gap is structural, where it is deliberate strategy, and what questions internal analytics access would answer.

## Methodology

Three independent data sources, cross-validated:

- **Google Trends PT** — relative search demand per brand and model, observed at stated dates with documented query strings. Index instability caveat applied throughout: all values are relative to the peak within the selected time window and are used as directional demand signals only.
- **Configurator observation** — each of five brand configurators walked on desktop (1440px) and mobile (390px) using a ten-checkpoint fieldwork checklist. Screenshots at every decision point. Observation dates stated per brand.
- **Annual reports 2024** — BMW Group, Audi Group, Mercedes-Benz Group, Volvo Cars, Porsche AG. Used to establish stated direct sales strategy per brand and cross-check against observed configurator behaviour.

GA4 proxy baseline: Google BigQuery public dataset (Google Merchandise Store, 344,640 sessions). Used for structural funnel patterns only — session-depth conversion lift (6.3x, first to sixth-plus session) and multi-session path to conversion (median 3 sessions, average 129h). Not automotive data. Not claimed as brand-specific.

## Repo structure

    methodology/     GA4 proxy baseline, Google Trends caveat, annual report extractions
    fieldwork/       configurator observation logs and paid mobile path findings
    brands/          brand-specific findings (Mercedes-Benz, BMW, Audi, Volvo, Porsche)
    assets/          screenshots (observation + Trends) and raw SQL/CSV from BigQuery
    matrix/          five-brand comparative matrix source
    dashboard/       final HTML audit document
    targeting/       company-specific application notes

## Key findings

- All five brands show measurable to exceptional search demand in Portugal
- No brand has activated online purchase in PT as of 27/06/2026
- Mercedes-Benz has the infrastructure (Online Store, eleven converted markets) but Portugal is not in scope
- BMW has deployed a reservation CTA on the i4 but not on the iX3 — the higher-demand model
- Volvo has built /shop/ URL architecture but resolves to a dealer form at the point of commitment
- Porsche's absence of a purchase CTA is confirmed strategy, not a gap

## Three testable hypotheses

- **H1** — Configurator end CTA is the single highest-value optimisation point across all five brands
- **H2** — Save mechanism friction suppresses return visit value (Audi carLOG finding is the clearest evidence)
- **H3** — Volvo PT is the most digitally advanced funnel — invalid. End CTA is dealer form only. /shop/ URL present but not activated.

## What this demonstrates

- SQL proficiency: four BigQuery queries with documented outputs in assets/methodology/
- Analytical discipline: hypotheses stated before observation, one self-invalidated on evidence
- Source rigour: every claim traceable to a screenshot, a query result, or an annual report page
- Communication: findings scoped precisely — limitations stated, open questions named, data access requirements explicit

## Observation expiry

Configurators change. All findings are valid at the stated observation dates only.

---

Sara M. S. Cruz · v1.0 · 27/06/2026
