---
layout: default
title: Green Agile Guide — Preview (v0.8)
description: A compact operating frame that integrates sustainability empirically into agile software development — without adding new meetings.
permalink: /guide/
---

# Green Agile Guide — Preview (v0.8)

> **Independence:** This guide has no affiliation with the official Scrum Guides, their authors, or Scrum.org. It builds on established agile concepts but was developed independently and extended with sustainability aspects.

---

## 1. Purpose and Positioning

The Green Agile Guide is an **operating frame for software products**. It extends proven agile ways of working with **clear rules, accountabilities, and measures** for ecological, economic, and social impact — **without** introducing new events or ceremonies. The goal is to make sustainable decisions **systematic, intentional, and measurable** in day-to-day development. The concepts are primarily for software and may be adapted to adjacent digital domains.

**Extension, not replacement:** The guide complements existing frameworks; it does not redefine them. It **bridges to the organization’s sustainability strategy** (e.g., CSRD/ESRS alignment) so product and corporate goals reinforce each other.

---

## 2. Foundations

### 2.1 Why agility and sustainability fit
Agile methods address uncertainty and complexity; sustainability is precisely such a long-horizon problem space. Empiricism makes impact **visible, testable, and adaptable** — using the same loops as for quality.

### 2.2 Three dimensions of sustainability
- **Ecological:** *Carbon awareness*, *energy efficiency*, *hardware efficiency* across the product life cycle.  
- **Economic:** Maintainability, technology choices, investment protection, TCO transparency.  
- **Social:** Accessible, inclusive products; fair team structures; psychological safety.  
The dimensions act together on **product and organization**.

### 2.3 Empiricism and sustainability
Empiricism relies on **transparency → inspection → adaptation**. Sustainability thus becomes **part of product and process quality**, not an external add-on: make impact visible, review it regularly, adapt when needed.

---

## 3. Values: Awareness & Responsibility

We add **two** values that make sustainability operational.

### Awareness
**Short definition:** We **pause before we act** — we name assumptions, side effects, and life-cycle consequences, and interpret measurements in context.  
**Behavioral anchors (excerpt):** Impact scan in refinement (user value, data/compute path, rebound, retention); surface uncertainties/biases; document decisions briefly and review them in retrospectives.  
**Anti-patterns:** “We’ll measure later”; wall-of-numbers without normalization; local optima causing rebound.

### Responsibility
**Short definition:** We **take responsibility** for the product’s environmental and social impact **across its life cycle** and decide based on **measurable effects**.  
**Behavioral anchors (excerpt):** Sustainability goals in product/iteration goals; make trade-offs explicit; criteria in **Definition of Ready** and **Green Definition of Done**; measurement/estimation with stated uncertainty.  
**Anti-patterns:** “Not our problem” (outsourcing impact); greenwashing; local optimization that increases the overall footprint.

---

## 4. Roles (no new roles)

Sustainability is **anchored in existing roles**; adding roles would fragment accountability.

- **Green Product Owner (GPO):** Defines “value” including measurable sustainability goals (e.g., SCI/WCAG/TCO), aligns the **Green Product Backlog** to a **Green Product Goal**, orders by impact and risk, makes trade-offs transparent, and links to corporate goals/CSRD.  
- **Green Developer Team (GDT):** Delivers a usable increment each **Development Iteration** that meets the **Green Definition of Done**; monitors proxy metrics (e.g., data/txn, CPU-time/txn), reduces hotspots, and records key architecture/data decisions (**ADR-Light**).  
- **Green Agile Coach (GAC):** Embeds practices in the process (budgets in planning, impact in review, green-focused retros), removes impediments (tooling/data access), and strengthens empiricism/system thinking. Optional: rotating **Sustainability Champion** “hat” (10–20% capacity) or enabling functions (e.g., GreenOps) across teams.

---

## 5. Green Product Backlog

The **Green Product Backlog** is the ordered list of all known needs for a sustainable product. **Each item** considers, besides user/business value, its ecological, economic, and social **impact** (direct/indirect). **Ordering** uses **value & impact**; priority goes to items that measurably advance the **Green Product Goal** or address **risk/compliance**.

**Definition of Ready (DoR):** Impact fields (direct/indirect, dimension, metric baseline→target, verification) are filled; there is an **alignment with the corporate sustainability strategy** (e.g., ESRS-relevant needs, EU taxonomy); relevant sustainability/compliance stakeholders are engaged.

---

## 6. Green Definition of Done (GDoD)

The GDoD is the **shared quality promise**: an increment is “done” when it is **functionally usable** **and** the agreed sustainability goals are met **or** justified deviations are made explicit and addressed promptly.

**Ecological (orientation):** Efficiency budgets (compute time, data volume, storage) respected; no unjustified regressions vs. baseline; data minimization & retention; no unnecessary idle/background load; at least **one impact-proximate metric** documented.  
**Economic:** Maintainable/scalable; no new technical debt without a follow-up plan; architecture supports operations & TCO transparency.  
**Social:** Relevant accessibility requirements met (e.g., WCAG 2.2 AA); ethical/legal/internal standards upheld.  
The GDoD is regularly **inspected and adapted** to keep contributing to sustainability goals.

---

## 7. Evolution

The Green Agile Guide evolves **iteratively**. Inputs from practice, research, and regulation (e.g., CSRD/ESRS) are incorporated. Organizations tailor the guide to their contexts; the core principles — **empiricism, self-accountability, and sustainable value creation** — remain unchanged.

---

### License & Notice
© mehr.wert Software und IT Beratung GmbH — **Preview**. All rights reserved. Independent from Scrum.org / Scrum Guide authors.