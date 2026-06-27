# Comparative Matrix — Five Brands × Five Dimensions

**Market:** Portugal  
**Last updated:** [FILL IN]  
**Status:** SKELETON — no cells filled until direct observation complete

Every cell must be filled from direct evidence. If data is unavailable, the cell reads "Not observed" with a note. No cell may be inferred from the GA4 proxy dataset.

---

## Matrix

| Dimension | Mercedes-Benz | BMW | Audi | Volvo | Porsche |
|-----------|--------------|-----|------|-------|---------|
| **1. Configurator end CTA** | Not observed | Not observed | Not observed | Not observed | Not observed |
| **2. Save mechanism** | Not observed | Not observed | Not observed | Not observed | Not observed |
| **3. Search demand vs digital readiness** | Not observed | Not observed | Not observed | Not observed | Not observed |
| **4. Paid mobile path** | Not observed | Not observed | Not observed | Not observed | Not observed |
| **5. Direct sales status PT** | Not observed | Not observed | Not observed | Not observed | Not observed |

---

## Dimension definitions

### 1. Configurator end CTA
What digital action is available at the end of a completed configuration.  
**Values:** Online purchase / Online reservation / Dealer form / No CTA  
**Source:** Direct configurator observation (Section 6, checkpoint 7)

### 2. Save mechanism
Whether configuration can be saved and what it requires.  
**Values:** First-party email-only / First-party account required / Third-party portal / None  
**Source:** Direct configurator observation (Section 6, checkpoint 5)

### 3. Search demand vs digital readiness
Highest-demand model in PT (Google Trends index) vs whether a digital purchase path exists for that model.  
**Values:** [Index score, observation date] vs [purchase path: yes / no / partial]  
**Source:** Google Trends PT + direct observation

### 4. Paid mobile path
Whether CPC traffic on mobile lands in-funnel or on a generic model page.  
**Values:** In-funnel / Generic model page / Not observed  
**Source:** Direct observation (Section 6, checkpoint 9)

### 5. Direct sales status PT
Whether online reservation or purchase is live in Portugal for any model.  
**Values:** Live / Not live / Partial (reservation only)  
**Source:** Direct observation + annual report

---

## Fill order

Fill Mercedes-Benz first. It is the priority brand for the target audience.

| Brand | Depends on | Status |
|-------|-----------|--------|
| Mercedes-Benz | Configurator walk + Trends session | Not started |
| BMW | iX3 fix resolved first | Blocked |
| Audi | Verify current state (configurator may have changed since June 26) | Partial |
| Volvo | Configurator walk + annual report | Not started |
| Porsche | Configurator walk — end screen only | Not started |

---

## Notes

- Dimensions that do not vary across brands are not in this matrix. If all five brands have a mobile configurator, that is noted once in the methodology section and dropped here.
- The matrix is the evidence base for H1, H2, and H3. No hypothesis can be stated until the relevant cells are filled.
- Porsche row: if end CTA is dealer-form-only, note it as deliberate high-touch positioning, not a digital gap. Context required.
