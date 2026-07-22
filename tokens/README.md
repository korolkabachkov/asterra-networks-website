# tokens

Design tokens — the single source of truth for the visual language. Consumed by
[`../components/`](../components/), [`../design-system/`](../design-system/), and the
eventual build [`../handoff/`](../handoff/).

**Input:** [`../concept/`](../concept/)

## Planned token sets (dark-first, editorial tech)

- [ ] **Color** — dark-first base + inset light surfaces, accent(s), semantic roles
- [ ] **Typography** — editorial scale (oversized display → body), families, weights
- [ ] **Spacing** — base unit + scale
- [ ] **Radius / borders**
- [ ] **Elevation / shadow**
- [ ] **Motion** — durations, easings (expressive; respect `prefers-reduced-motion`)
- [ ] **Breakpoints** — desktop-first, full mobile

Format (planned): tokens as JSON, exported to CSS custom properties.

**Status:** _Not started._
