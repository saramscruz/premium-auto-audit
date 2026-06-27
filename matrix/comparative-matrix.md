# Comparative Matrix — Five Brands × Five Dimensions

**Market:** Portugal  
**Last updated:** 27/06/2026  
**Status:** Mercedes-Benz complete. BMW partial. Audi partial. Volvo and Porsche not started.

Every cell must be filled from direct evidence. If data is unavailable the cell reads "Not observed" with a note. No cell may be inferred from the GA4 proxy dataset.

---

## Matrix

| Dimension | Mercedes-Benz | BMW | Audi | Volvo | Porsche |
|-----------|--------------|-----|------|-------|---------|
| **1. Configurator end CTA** | Dealer form only — "Solicitar proposta" via Online Store; "Solicitar veículo agora" on configured path. "Compra direta online" language present but not implemented. Observed 27/06/2026 | iX3: no Reserve CTA at step 14. i4: Reserve CTA at step 12. Observed 12/06/2026 | "Solicitar uma proposta" — dealer form only. Observed 26/06/2026 | Not observed | Not observed |
| **2. Save mechanism** | First-party account required — Mercedes me ID login wall. Secondary path: OnlineCode share mechanism (no login). Observed 27/06/2026 | Not observed | Third-party — carLOG, with expiry warning. Observed 26/06/2026 | Not observed | Not observed |
| **3. Search demand vs digital readiness** | CLA avg index 76, "cla 2026" +1,300%, "mercedes glc 2026" +4,550% — no digital purchase path. Observed 27/06/2026 | iX3 "ix3 2026" +750% (12/06/2026), BREAKOUT by 26/06/2026 — i4 has Reserve, iX3 does not | Q3 Sportback BREAKOUT — dealer form only. Observed 26/06/2026 | Not observed | Not observed |
| **4. Paid mobile path** | Not observed | Not observed | Not observed | Not observed | Not observed |
| **5. Direct sales status PT** | Not live — Online Store infrastructure exists, "Compra direta online" language present, resolves to dealer form. Observed 27/06/2026 | Not live — BMW brand Europe direct sales planned for later date (BMW Group Report 2024) | Not live — dealer form only (BMW Group Report 2024 confirms VW Group same position) | Not observed | Not observed |

---

## Dimension definitions

### 1. Configurator end CTA
What digital action is available at the end of a completed configuration.
Values: Online purchase / Online reservation / Dealer form / No CTA
Source: Direct configurator observation (Section 6, checkpoint 7)

### 2. Save mechanism
Whether configuration can be saved and what it requires.
Values: First-party email-only / First-party account required / Third-party portal / None
Source: Direct configurator observation (Section 6, checkpoint 5)

### 3. Search demand vs digital readiness
Highest-demand model in PT (Google Trends index) vs whether a digital purchase path exists for that model.
Values: [Index score, observation date] vs [purchase path: yes / no / partial]
Source: Google Trends PT + direct observation

### 4. Paid mobile path
Whether CPC traffic on mobile lands in-funnel or on a generic model page.
Values: In-funnel / Generic model page / Not observed
Source: Direct observation (Section 6, checkpoint 9)

### 5. Direct sales status PT
Whether online reservation or purchase is live in Portugal for any model.
Values: Live / Not live / Partial (reservation only)
Source: Direct observation + annual report

---

## Fill order

| Brand | Status |
|-------|--------|
| Mercedes-Benz | Complete — all observed dimensions filled |
| BMW | Partial — iX3 figure resolved, end CTA confirmed, direct sales confirmed not live |
| Audi | Partial — end CTA and save mechanism confirmed, Trends needs date update |
| Volvo | Not started — H3 depends on this |
| Porsche | Not started — end screen only needed |
