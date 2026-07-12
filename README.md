# OSHA Stair & Rail Code Check

> Instant lookup tool for 29 CFR 1910 stairway and railing requirements — built for structural engineers designing miscellaneous steel stairs.

**[🔗 Live Demo →](https://vibhanshu-mishra.github.io/osha-stair-rail-code-check/)**

---

## What Is This?

A fully self-contained, offline-capable HTML reference tool that lets you look up OSHA stairway and railing dimensional requirements in plain English — with exact CFR citations for every answer.

No API calls. No login. No installation. Just open the file (or visit the GitHub Pages link above) and start searching.

Built by a structural engineer who got tired of digging through the CFR mid-design.

---

## What It Covers

16 curated provisions from **29 CFR 1910 Subpart D (Walking-Working Surfaces)**:

**From 29 CFR 1910.25 — Stairways**
- Maximum riser height (standard stairs)
- Minimum tread depth (standard stairs)
- Minimum stairway width
- Stair angle range (30°–50°)
- Minimum vertical clearance/headroom
- Spiral stair tread depth and headroom
- Landing/platform size requirements
- Stair load capacity requirements
- When standard vs. spiral/alternating-tread stairs are required

**From 29 CFR 1910.28–.29 — Stair Rail Systems & Handrails**
- Handrail height (30–38 in)
- Stair rail system height for **new installations** (on or after Jan 17, 2017) → 42 in
- Stair rail system height for **existing installations** (before Jan 17, 2017) → 30 in, with combo top rail rules
- Minimum finger clearance (2.25 in)
- Maximum opening in stair rail systems (19 in)
- Handrail/stair rail strength requirement (200 lb)
- When guardrails/stair rail systems are required at landings (4 ft+ above lower level)

---

## How It Works

Type a plain-English question or keyword (e.g. *"handrail height"*, *"max riser"*, *"spiral stair"*, *"42 inches"*) and the tool instantly searches the knowledge base using keyword scoring. The best-matching provision is displayed as a card with the full CFR citation.

No network connection required — all logic and content is embedded in a single HTML file.

---

## Example Queries

```
Max riser height, standard stairs?
Stair rail height for new construction?
Can the top rail double as a handrail?
Spiral stair tread depth?
When is a guardrail required at a landing?
Handrail strength requirement?
What is the minimum stair width?
```

---

## How to Use

**Option 1 — Live (GitHub Pages):**
Visit the live demo link above. No setup required.

**Option 2 — Local:**
1. Download `osha-stair-rail-assistant.html`
2. Open it in any modern browser
3. Works completely offline

---

## ⚠️ Disclaimer

This tool is a **quick reference only** — not a substitute for the full regulation text, your Authority Having Jurisdiction (AHJ), or a licensed engineer's review.

Always verify against the current text of **29 CFR 1910.25** and **1910.28–.29** at [eCFR.gov](https://www.ecfr.gov), especially for provisions noting an open 2021 NPRM. OSHA regulations are subject to change.

---

## 🗺️ Roadmap

- [x] 16 OSHA 29 CFR 1910.25 & 1910.28–.29 provisions (stairways + stair rail systems)
- [ ] ADA Standards for Accessible Design (2010), Sections 504–505 — handrail extensions, graspability, closed risers, nosing limits, with clear `[OSHA]` vs `[ADA]` labeling where requirements conflict
- [ ] IBC stair provisions (user-supplied reference — bring your own licensed copy)
- [ ] Printable one-page code summary PDF

---

## 👷 About

Built by **Vibhanshu Mishra, PE** — Structural Engineer at AG&E Structural Engenuity, Austin, TX.

Specialising in steel and mission-critical structures, with a side focus on miscellaneous structures — stairs, platforms, equipment supports. Building AI and automation tools for a niche that nobody else is covering yet.

- 🔗 [RISA-3D MCP Server](https://github.com/vibhanshu-mishra/risa3d-mcp-server) — Connect Claude AI to your RISA-3D structural models
- 🔗 [TSD MCP Server](https://github.com/vibhanshu-mishra/tsd-mcp) — Connect Claude AI to your TSD structural models
- 💼 Connect on [LinkedIn](https://www.linkedin.com/in/vibhanshu9/)

---

The regulation text referenced (29 CFR 1910) is published by the U.S. Government and is in the public domain.
