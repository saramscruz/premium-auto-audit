# Comparative Matrix — Five Brands × Five Dimensions

**Market:** Portugal
**Last updated:** 27/06/2026
**Status:** Mercedes-Benz complete. BMW partial. Audi partial. Volvo observation complete, Trends outstanding. Porsche not started.

Every cell must be filled from direct evidence. If data is unavailable the cell reads "Not observed" with a note. No cell may be inferred from the GA4 proxy dataset.

---

## Matrix

| Dimension | Mercedes-Benz | BMW | Audi | Volvo | Porsche |
|-----------|--------------|-----|------|-------|---------|
| **1. Configurator end CTA** | Dealer form only — "Solicitar proposta" via Online Store; "Solicitar veículo agora" on configured path. "Compra direta online" language present but not implemented. Observed 27/06/2026 | iX3: dealer form only — no Reserve at step 14. i4: "Reservar" CTA present at step 12. Gap is model-specific. Observed 12/06/2026 | "Solicitar uma proposta" — dealer form only. Observed 26/06/2026 | "Pedir proposta" — dealer form only. /shop/ URL infrastructure present, purchase not activated. Observed 27/06/2026 | Not observed |
| **2. Save mechanism** | First-party account required — Mercedes me ID login wall. Secondary: OnlineCode share (no login). Observed 27/06/2026 | First-party — "Guardar Configuração" (login status outstanding) + frictionless "Link do seu BMW" (no login). Observed 12/06/2026 | Third-party — carLOG with expiry warning. Observed 26/06/2026 | Frictionless — "Copiar link" (no login) + PDF download (no login) + "Código da configuração". "Guardar" login status outstanding. Observed 27/06/2026 | Not observed |
| **3. Search demand vs digital readiness** | CLA avg index 76, "cla 2026" +1,300%, "mercedes glc 2026" +4,550% — dealer form only. Observed 27/06/2026 | iX3 "ix3 2026" +750% (12/06/2026), BREAKOUT by 26/06/2026, avg index 48 — iX3 dealer form only, i4 Reserve available | Q3 avg index 51, "audi q3 2026" +700% — dealer form only. Observed 26/06/2026 | Trends session outstanding | Not observed |
| **4. Paid mobile path** | Not observed | Not observed | Not observed | Not observed | Not observed |
| **5. Direct sales status PT** | Not live — "Compra direta online" language present, resolves to dealer form. Observed 27/06/2026 | Not live — BMW brand Europe direct sales planned for later date (BMW Group Report 2024). i4 Reserve is reservation not purchase. | Not live — dealer form only. Observed 26/06/2026 | Not live — /shop/ infrastructure built, purchase CTA not activated in PT. Observed 27/06/2026 | Not observed |

---

## H3 verdict

**INVALID.** Volvo PT configurator end CTA is "Pedir proposta" — dealer form only. Online purchase not live. The thesis holds uniformly across all five brands observed. Volvo is not the thesis exception.

---

## Dimension definitions

### 1. Configurator end CTA
What digital action is available at the end of a completed configuration.
Values: Online purchase / Online reservation / Dealer form / No CTA
Source: Direct configurator observation (Section 6, checkpoint 7)

### 2. Save mechanism
Whether configuration can be saved and what it requires.
Values: First-party email-only / First-party account required / Third-party portal / Frictionless (no login) / None
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
Values: Live / Not live / Partial (reservation only) / Infrastructure present, not activated
Source: Direct observation + annual report

---

## Fill order

| Brand | Status |
|-------|--------|
| Mercedes-Benz | Complete |
| BMW | Partial — mobile end screen and Guardar login status outstanding |
| Audi | Partial — entry CTA verbatim, step count, account requirement outstanding |
| Volvo | Observation complete — Trends and Guardar login status outstanding |
| Porsche | Not started — end screen only needed |
