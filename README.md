# Subspace.money — Product Teardown 2026

**Assignment:** Vocallabs.ai / Subspace.money Product Intern Assignment  
**Deadline:** 31 May 2026, 11:59 PM IST  
**Company chosen:** Subspace.money

---

## What's in this repo

| File | Description |
|------|-------------|
| `index.html` | Full visual teardown report — open in any browser |
| `README.md` | This file — structured summary of all 5 feedbacks |

## How to view the report

Open `index.html` in your browser, or view it via GitHub Pages if the repo has Pages enabled.

---

## Company Snapshot

- **What:** India's first subscription marketplace + group sharing platform for OTT, local services, and rentals
- **Revenue (FY25):** ₹36.5 Cr ARR — bootstrapped, zero external funding
- **Moats:** Negotiate API · Local marketplace network effects · India-first positioning

---

## Five Feedbacks

### 01 · UX / Trust — Shared subscription admins are strangers with no accountability layer

**Observed:** Public group admins can collect money from strangers with only a basic rating. Play Store reviews document multiple cases of users paying and being locked out with no refund.

**Problem:** Trust collapse at the core transaction kills the network-effect flywheel Subspace needs. One bad experience = permanent churn + damaging public review.

**Ship instead:** Launch **Subspace-Verified Admin** — Aadhaar KYC + ₹500–₹1,000 escrow deposit. Add a "Protected Purchase" badge on verified groups. Subspace guarantees a refund if access isn't delivered within 24 hours.

---

### 02 · GTM / Activation — The homepage asks users to log in before showing them any value

**Observed:** subspace.money on desktop shows only a login prompt and a loading skeleton. No deals, no prices, no social proof. You must submit your phone number before seeing a single product.

**Problem:** Login-before-value is a conversion killer in a trust-sensitive category. Paid and organic acquisition clicks bounce with no conversion.

**Ship instead:** Build a **public browse mode** — show live deals (e.g., "Netflix Premium @ ₹149/month shared with 3 others") without login. Gate only at checkout. Add above-fold social proof: "2L+ users saving ₹400/mo."

---

### 03 · Features / Retention — The Negotiate API is invisible; users don't know it exists

**Observed:** Subspace markets the Negotiate API as a key moat. In the app, there's no UI surface for it — no savings tracker, no negotiation state, no monthly summary of what was saved.

**Problem:** A moat users can't perceive creates zero loyalty and zero virality. The feature is also a natural share moment ("Subspace saved me ₹300 this month") that's completely unused.

**Ship instead:** Build a **Savings Story** — monthly push notification + in-app card: "Subspace negotiated ₹180 off Canva, ₹120 off YouTube. Total: ₹300 saved." Add a **Negotiation Tracker** on each subscription detail page showing original vs. negotiated price.

---

### 04 · Competitor Analysis / Positioning — Subspace competes on "cheap OTT" when its real moat is the local marketplace

**Observed:** Primary copy leads with "up to 80% off on Netflix, Prime, YouTube" — identical to grey-market Telegram groups. The local subscription marketplace (gyms, tiffins, local SaaS) appears only at the bottom of the site.

**Problem:** Competing on price with zero-compliance Telegram groups is a race to zero. The defensible moat is the hyperlocal marketplace — network effects that no reseller can replicate.

**Ship instead:** Redesign GTM around **"Your City's Subscription Hub"**. Launch city-specific landing pages. Run a Local Provider Sprint: 50 gyms/tiffin services in one city, onboarded in 30 days. This builds the flywheel on the most defensible terrain.

---

### 05 · Potential Collaborations / Distribution — WhatsApp login is the entire funnel; no B2B surface exists

**Observed:** Only signup method is WhatsApp/OTP. No employer portal, no college bundle, no HRMS integration. Business API docs exist for providers listing themselves, not for distribution partners.

**Problem:** 100% D2C acquisition with rising CAC and no distribution leverage. Group sharing and the Negotiate API are naturally suited to B2B2C but no such channel is being built.

**Ship instead:** Pilot **Subspace for Teams** — partner with 5–10 Indian tech companies to offer subscription perks bundles as employee benefits (low cost for HR; near-zero CAC for Subspace). Also pitch **Fi Money / Niyo / HDFC SmartHub** for an embedded "Subscription Manager" widget inside their apps.

---

## Prioritisation Logic

| # | Feedback | Impact | Effort | When |
|---|----------|--------|--------|------|
| 01 | Verified Admin + Escrow | Critical | Medium | Sprint 1 |
| 02 | Public Browse Mode | High | Low | Sprint 1 |
| 03 | Savings Story / Negotiate Tracker | High | Low | Sprint 2 |
| 04 | City-first GTM Pivot | Medium | High | Sprint 2–3 |
| 05 | Subspace for Teams / Neobank Embed | High | High | Q3 |

---

## Frameworks Used

- **SWOT** (full matrix in the HTML report)
- **Porter's Five Forces** (referenced in Feedback 04 re: barriers to entry in hyperlocal)
- **Jobs-to-be-Done** (underlying each problem statement)
- **ICE scoring** (implicit in the prioritisation table)

---

## Research Sources

- Subspace.money — website and web app (used as a real user)
- Google Play Store listing + user reviews
- Business Upturn (CEO appointment article, March 2026)
- Tracxn (competitor landscape, financials)
- Product Hunt (user sentiment)
- RevenueCat State of Subscription Apps 2026

---

*Open `index.html` for the full visual report.*
