# Comparative Matrix — Five Brands × Five Dimensions

**Market:** Portugal
**Last updated:** 27/06/2026
**Status:** All five brands observed. Trends outstanding for Volvo and Porsche. Mobile outstanding for Porsche.

Every cell must be filled from direct evidence. If data is unavailable the cell reads "Not observed" with a note. No cell may be inferred from the GA4 proxy dataset.

---

## Matrix

| Dimension | Mercedes-Benz | BMW | Audi | Volvo | Porsche |
|-----------|--------------|-----|------|-------|---------|
| **1. Configurator end CTA** | Dealer form — "Solicitar proposta" (stock path) + "Solicitar veículo agora" (configured path). "Compra direta online" language present but not implemented. Observed 27/06/2026 | iX3 step 14: dealer form only, no Reserve. i4 step 12: "Reservar" present. Gap is model-specific not brand-level. Observed 12/06/2026 | "Solicitar uma proposta" — dealer form only. Observed 26/06/2026 | "Pedir proposta" — dealer form only. /shop/ URL infrastructure present, purchase not activated. Observed 27/06/2026 | "Solicitar este veículo" — dealer request only. Deliberate high-touch positioning at 108.016€ base price. Observed 27/06/2026 |
| **2. Save mechanism** | First-party account required — Mercedes me ID. Secondary: OnlineCode share (frictionless). Observed 27/06/2026 | "Guardar Configuração" (login status outstanding) + "Link do seu BMW" (frictionless). Observed 12/06/2026 | Third-party carLOG with expiry warning — only third-party save in comparison. Observed 26/06/2026 | "Copiar link" (frictionless) + PDF download (frictionless) + Código da configuração. "Guardar" login status outstanding. Lowest friction save in comparison. Observed 27/06/2026 | "Criar Porsche Code" (frictionless) + PDF download (frictionless). "Guardar" login status outstanding. Observed 27/06/2026 |
| **3. Search demand vs digital readiness** | CLA avg index 76 (highest in comparison), "mercedes glc 2026" +4,550% — dealer form only. Observed 27/06/2026 | iX3 avg index 48, "ix3 2026" +750% (12/06/2026), BREAKOUT by 26/06/2026 — iX3 dealer form, i4 Reserve available | Q3 avg index 51, "audi q3 2026" +700% — dealer form only. importrust parity signal (index 52). Observed 26/06/2026 | Trends outstanding | Trends outstanding |
| **4. Paid mobile path** | Not observed | Not observed | Not observed | Not observed | Not observed |
| **5. Direct sales status PT** | Not live — "Compra direta online" language present, resolves to dealer form. Observed 27/06/2026 | Not live — BMW brand Europe direct sales planned for later date (BMW Group Report 2024). i4 Reserve is reservation not purchase. | Not live — dealer form only. Observed 26/06/2026 | Not live — /shop/ URL infrastructure built, purchase CTA not activated. Observed 27/06/2026 | Not live — deliberate high-touch model at 108.016€+ price point. Observed 27/06/2026 |

---

## H3 verdict

**INVALID.** Volvo PT end CTA is "Pedir proposta" — dealer form only. Online purchase not live. The thesis holds uniformly across all five brands. No brand in the comparison has activated online purchase in Portugal as of 27/06/2026.

---

## Save mechanism classification — ranked by friction (lowest to highest)

1. **Volvo** — frictionless link copy + PDF, no login required for any save path
2. **Porsche** — Porsche Code (frictionless) + PDF, Guardar status outstanding
3. **BMW** — frictionless link share confirmed, Guardar login status outstanding
4. **Audi** — third-party (carLOG) with expiry warning — external dependency
5. **Mercedes-Benz** — first-party account required (Mercedes me ID) for primary save path

---

## Dimension definitions

### 1. Configurator end CTA
What digital action is available at the end of a completed configuration.
Values: Online purchase / Online reservation / Dealer form / Dealer request / No CTA
Source: Direct configurator observation (Section 6, checkpoint 7)

### 2. Save mechanism
Whether configuration can be saved and what it requires.
Values: First-party account required / Third-party portal / Frictionless (no login) / None
Source: Direct configurator observation (Section 6, checkpoint 5)

### 3. Search demand vs digital readiness
Highest-demand model in PT (Google Trends index) vs whether a digital purchase path exists.
Values: [Index score, observation date] vs [purchase path: yes / no / partial]
Source: Google Trends PT + direct observation

### 4. Paid mobile path
Whether CPC traffic on mobile lands in-funnel or on a generic model page.
Values: In-funnel / Generic model page / Not observed
Source: Direct observation (Section 6, checkpoint 9)

### 5. Direct sales status PT
Whether online reservation or purchase is live in Portugal for any model.
Values: Live / Not live / Infrastructure present not activated / Deliberate high-touch model
Source: Direct observation + annual report

---

## Outstanding

| Brand | Outstanding |
|-------|-------------|
| Mercedes-Benz | Annual report extraction, checkpoint 9 paid search |
| BMW | Mobile end screen, Guardar login confirmation |
| Audi | Entry CTA verbatim, step count, account requirement re-walk |
| Volvo | Trends session, Guardar login confirmation, annual report |
| Porsche | Trends session, mobile end screen, Guardar login confirmation, annual report |
