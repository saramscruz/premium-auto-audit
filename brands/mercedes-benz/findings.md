# Mercedes-Benz — Brand Findings

**Status:** Configurator observation complete — 27/06/2026  
**Model walked:** CLA 200 com tecnologia EQ (Elétrico)  
**URL:** mercedes-benz.pt/passengercars/models/saloon/cla-electric/overview.html  
**Observation date:** 27/06/2026  

---

## Distinctive finding

Mercedes PT uses "Compra direta online" language and an "Online Store" breadcrumb on the end screen — but both resolve to dealer lead forms ("Solicitar proposta"). The gap between stated digital capability and implemented reality is the sharpest single finding in the document. Mercedes is further along in direct-to-consumer language than BMW or Audi, but has not yet closed the loop to a true online purchase or reservation in Portugal.

---

## Checkpoint findings — 27/06/2026

### 1. Entry CTA
Two CTAs in sticky bottom bar on model page:
- "Configure o seu veículo" — secondary style (white/outline)
- "Descubra os veículos disponíveis" — primary style (blue filled)

Mercedes leads with stock availability as the primary action, not configuration. Distinct from BMW and Audi which lead with configuration.

### 2. Configurator structure
Sidebar navigation with 9 top-level sections — not numbered sequential steps:
Arranque rápido · Motorizações · Variantes · Exterior · Interior · Multimédia · Sistemas de assistência e segurança · Carregamento · Resumo

Variantes and Exterior each contain 4 sub-sections. Total depth is greater than the top-level count suggests. Architecturally different from BMW (14 sequential steps) and Audi.

### 3. Price visibility
Visible from the first configurator screen (49.450€). Updates in real time on selection — confirmed: selecting Pintura Metalizada preto Cosmic (+950€) updated header immediately to 50.400€. Financing calculation ("Cálculo Financeiro") appears inline in the header when a paid option is selected.

### 4. Stock signal
Absent during configuration. Appears at end screen only — "Veículos de stock diretamente disponíveis" with similarity matching (99% semelhante). Three stock vehicles shown with prices and availability indicators.

### 5. Save mechanism
"Guardar" button prominent top right (blue, always visible). Clicking redirects immediately to full-page Mercedes me ID login wall (id.mercedes-benz.com/ciam/auth/login). Requires email or phone number — account creation mandatory.

**Classification: First-party account required.** Highest friction save mechanism in the comparison.

### 6. Expiry warning
Not observed.

### 7. End screen CTA
Three paths presented at "Passo seguinte":
- "Guardar a configuração" → Mercedes me ID login wall
- "Solicitar veículo agora" → dealer lead form
- "Mostrar veículos disponíveis" → stock listing with "Ir para loja online"

"Ir para loja online" on stock cards leads to mercedes-benz.pt/passengercars/buy/new-car/product.html — breadcrumb reads "Online Store › Veículos" but the sole CTA is "Solicitar proposta" (dealer lead form).

**Classification: Dealer form only. Online purchase not live in PT.**

### 8. Mobile parity
Confirmed identical at 390px. Same CTAs, same price, same structure. "Descubra os veículos disponíveis" (primary, blue) + "Contacte-nos" (secondary). Full parity.

### 9. Paid entry point
Not observed during session. No paid search ad visible for Mercedes PT on 27/06/2026.

### 10. Account requirement
Configurator completion does not require login. Save requires Mercedes me ID account. Online Store "Solicitar proposta" — login status not tested.

---

## Additional signals

**"Introduzir OnlineCode"** — present on mobile and desktop at the Motorizações screen. Allows entry of a pre-configured code to jump directly to a saved configuration. Functions as a share/re-entry mechanism that bypasses the login wall — a second save path not visible in the main Guardar flow.

**"Contém MBUX"** badge on Edition ONE special variant (+12.350€). MBUX Digital surfaced as a premium add-on within the configurator.

**"Mais comprado" social proof labels** appear on both motorização variants and paint options. Consistent purchase frequency signalling throughout the funnel.

**"mercedes usados certificados" +110%** rising query from BMW audit — investigate whether Mercedes PT has a separate used car digital funnel. The Online Store infrastructure (mercedes-benz.pt/passengercars/buy/) may extend to CPO vehicles.

---

## Confirmed findings for matrix

| Dimension | Finding |
|-----------|---------|
| Configurator end CTA | Dealer form only ("Solicitar proposta") — online purchase not live in PT |
| Save mechanism | First-party account required (Mercedes me ID) |
| Search demand vs digital readiness | CLA Elétrico from 49.450€ — Trends session outstanding |
| Paid mobile path | Not observed |
| Direct sales status PT | Not live — "Compra direta online" language present but resolves to dealer form |

---

## Outstanding

- [ ] Google Trends PT session for CLA and EQA — establish highest-demand model and index score
- [ ] Mercedes-Benz Group Annual Report 2024 — extract direct sales market rollout and MBUX Digital strategy statements
- [ ] Verify "mercedes usados certificados" +110% — check whether Online Store extends to CPO
- [ ] Checkpoint 9 — run paid search observation separately: search "cla elétrico" and "mercedes cla" in PT incognito and record where any paid ad lands
