# Research — Asterra Networks

> **Phase:** Discovery. This document captures the research that feeds the
> information architecture, content model, and design direction.
> Full design brief: [`../CLAUDE.md`](../CLAUDE.md) · Repo index: [`../README.md`](../README.md)

---

## 1. Objective

Understand how a **global connectivity + cybersecurity + mission-systems provider**
presents a large, complex catalog so that a professional buyer can, in a few clicks:

1. find the solution relevant to **their industry**,
2. understand its **value and proof**, and
3. **reach an expert** (submit an inquiry).

Primary user to optimize for: **maritime shipowners / fleet operators** (see brief §4).

---

## 2. Method

- **Structural analysis** of category-leading global connectivity/security providers —
  we study *IA patterns and content types only*. No names, copy, product names,
  logos, or brand assets are reproduced (see brief constraints).
- **Content-type inventory** — catalog the reusable page/section types the domain relies on.
- **Persona synthesis** — map decision drivers per audience to page requirements.
- **Reference captures** — annotated screenshots kept in [`screens/`](./screens/) for
  structural reference (brand-identifying elements omitted/blurred).

---

## 3. Reference IA patterns (category analysis)

Common patterns observed across the category:

- **Dual entry model:** buyers arrive either "I know the *capability* I need"
  (Solutions) or "I represent *this sector*" (Industries). Category leaders serve both,
  cross-linked. → We adopt **two independent sections + cross-links** (brief §5).
- **Solution overview → category → (optional) product** depth, kept shallow (2–3 levels).
- **Industry pages** act as curated landing pages that re-package solutions in the
  sector's language and surface sector-specific proof.
- **Inquiry lives on the leaf pages**, not the homepage. The homepage sells
  *exploration* ("Discover our solutions"); the contextual **"Talk to an Expert" /
  "Send an Inquiry"** CTA appears on solution/service pages. → Confirmed in brief §6.
- **Trust scaffolding is everywhere:** coverage/scale stats, standards & compliance
  badges, support/SLA promises, and case proof.
- **Resource Center** (whitepapers, datasheets, guides) supports the technical buyer's
  self-education and doubles as a secondary conversion.

---

## 4. Content-type inventory

Reusable building blocks the design system must support:

| Content type | Purpose | Notes |
|---|---|---|
| Hero (exploration) | Homepage entry | "Discover our solutions" + routes to Solutions/Industries/News |
| Solution overview | Index of 5 categories | + **Solution Finder** entry |
| Solution / service page | Explain a capability | Carries **Send an Inquiry / Talk to an Expert** CTA |
| Industry page | Sector-framed landing | Re-packages solutions + sector proof |
| Solution Finder | Guided filter | By **industry** × **need** |
| Proof block | Trust | Coverage stats, standards/compliance, SLA, logos-slot (fictional) |
| Case study / story | Evidence | (Content type reserved; section out of initial scope) |
| Insights / News | Thought leadership | Article list + detail |
| Resource card / download | Lead-gen | Ungated default; optional email gate on premium assets |
| Careers | Employer brand | Role list + detail |
| Contact / Submit-a-Request | Conversion | Simple form, no wizard |

---

## 5. Audience & persona synthesis

| Audience | Leads narrative? | Top decision drivers | Page implications |
|---|---|---|---|
| Maritime — shipowners / fleet ops | **Yes (#1)** | Global coverage, uptime, maritime safety, compliance, support | Homepage tone; coverage & reliability proof up front |
| Enterprise IT & security | No | Security posture, integration, compliance | Cybersecurity + Digital Solutions depth |
| Government / public / defense | No | Standards, sovereignty, mission-critical | Compliance & assurance framing |
| Energy & critical infrastructure | No | Monitoring, IoT, uptime | Digital Solutions, remote ops proof |
| Transportation & delivery | No | Tracking, connectivity at scale | Coverage + data solutions |
| Research | No | Data transfer, remote connectivity | Connectivity + data services |
| Emergency response | No | Rapid deploy, resilience | Reliability + rapid-deploy proof |

Shared across all: **reliability · global coverage · security · compliance · support access.**

---

## 6. Key findings → design implications

1. **Lead with exploration, not the hard sell.** Homepage optimizes for wayfinding
   into Solutions/Industries; inquiry CTAs live on leaf pages. *(→ IA §5–6)*
2. **Two clear doorways** (capability vs. sector) reduce the cognitive load of a large
   catalog. *(→ nav + overview pages)*
3. **The Solution Finder is the hero interaction** for undecided buyers — filter by
   industry × need. *(→ components, design-system)*
4. **Trust must be continuous** — coverage/scale, standards, and support promises
   repeated as reusable proof blocks. *(→ component library)*
5. **Editorial-tech, dark-first** direction fits a technical, premium, mission-focused
   tone and lets bento/proof blocks carry dense information confidently. *(→ concept, tokens)*
6. **Maritime-first framing** on the homepage without alienating other sectors —
   achieved via a sector switcher / industry rail rather than maritime-only visuals.

---

## 7. Screens (reference captures)

Annotated structural references live in [`screens/`](./screens/). They document
*layout and content-type patterns only*; brand-identifying elements are omitted.
See that folder's README for the capture list and annotation conventions.

---

## 8. Open questions / next

- Confirm KPI targets and any real analytics goals (brief §14).
- Decide Solution Finder logic depth (simple filter vs. guided questionnaire).
- Confirm Resource Center gating policy per asset tier.
- Validate maritime-first homepage framing against secondary-persona needs.

**Next stage:** low-fidelity [`../wireframes/`](../wireframes/) for Home,
Solutions overview, a Solution page (with inquiry CTA), an Industry page, and the
Solution Finder.

---

## 9. Change log

- Discovery kickoff — objectives, method, IA patterns, content-type inventory, and
  persona synthesis captured from the approved brief.
