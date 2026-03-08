# The Great War: Data Story & Visualization Critique

## [https://www.poppyfield.org/]

---

## Introduction

Poppyfield.org uses the poppy flower as both visual metaphor and data glyph to narrate over a century of human conflict. This document tells that story through the data the visualization presents, while examining how effectively the design choices communicate it.

---

## A Century of Conflict

From 1900 to 2014, the Poppyfield dataset records more than 200 armed conflicts, an average of nearly two new wars per year. The distribution is far from uniform.

The first half of the 20th century is defined by two catastrophic peaks: WWI (1914-1918) and WWII (1939-1945), which together account for an estimated 90-100 million casualties. The Cold War era then brought a proliferation of proxy wars and independence struggles across Asia, Africa, and Latin America, with higher *frequency* but smaller per-event scale. Post-1990, conflict became geographically fragmented across the Balkans, the Middle East, and Central Africa.

**Key observation:** The 20th century is not a story of increasing peace interrupted by two world wars. It is a story of persistent, geographically shifting violence.

---

## How the Poppy Encodes This

The visualization maps four data dimensions onto the poppy:

- **X-axis** - Start year
- **Y-axis** - Duration (logarithmic scale)
- **Bloom size** - Casualty count
- **Color/petals** - Geographic region

The X-axis is intuitive and effective. The **logarithmic Y-axis** is technically sound (wars range from weeks to decades), but casual viewers may not register that a six-month war and a six-year war look visually similar in height.

The biggest design challenge is **bloom size for casualties**. WWII's 70-85 million deaths is five to six orders of magnitude larger than small conflicts, but a proportionally accurate poppy would dwarf the entire canvas. The visualization uses a compressed scale, which means bloom size conveys relative category (small, large, catastrophic) rather than precise magnitude. An explicit legend mapping size to casualty ranges would help viewers calibrate their reading.

---

## Where Wars Happened

The regional filter reveals a clear geographic shift:

- **Pre-1945:** European conflicts dominate in scale and cultural prominence.
- **1945-1990:** Asia becomes the dominant theater; African conflicts multiply as colonial empires collapse.
- **1990-2014:** Africa becomes the most conflict-dense region. The Second Congo War (1998-2003, approx. 5.4 million deaths) is one of the deadliest conflicts of the entire dataset.

This geographic story runs counter to the narrative implied by the poppy symbol itself. The poppy as memorial originates from the Western Front of WWI, encoding a specifically European experience. Yet the data shows that post-1945 conflict has been overwhelmingly borne by non-European nations, a tension the visualization does not address.

---

## Conclusion

Poppyfield succeeds as a memorial and as an introduction to the scale of 20th-century conflict. It makes over 200 wars legible at a glance in a way that respects their gravity. As a data analysis tool, however, the logarithmic scale can mislead, bloom-size encoding sacrifices precision, and the poppy symbol carries a cultural framing that shapes which conflicts feel central.

The most honest reading of Poppyfield is as a gateway, not a destination. Its success is in making viewers want to look further.

---
---

# Part 2: Data Story — SDG 16: Is the World Becoming More Peaceful?

## Sustainable Development Goal 16: Peace, Justice and Strong Institutions

---

## The Question

Our Part 1 analysis of Poppyfield revealed over 200 armed conflicts in a single century and a geographic shift from Europe to Asia to Africa. This raises a broader question tied to SDG 16:

**Is the world actually becoming more peaceful?**

---

## The Data Story

**Dataset:** Uppsala Conflict Data Program (UCDP) — tracks every armed conflict worldwide since 1946.

### Imagined Chart 1: Active Conflicts Per Year (1950–2024)

A **line chart** showing the number of active armed conflicts per year.

- **1950s–1980s:** Steady rise during the Cold War as proxy wars multiply.
- **1989–1992:** Sharp dip as the Cold War ends — the "peace dividend."
- **2010–2024:** Conflicts climb again, reaching **59 active conflicts in 2023** — the highest number since records began.

**Insight:** The post-Cold War peace was temporary. The world is not trending toward peace.

---

## Conclusion

SDG 16 envisions "peaceful and inclusive societies" by 2030. The data suggests we are moving in the opposite direction. While large-scale interstate wars have declined, the total number of active conflicts is at a record high, driven by civil wars and foreign interventions. Peace is not the default — it requires active investment.

**Data sources:** Uppsala Conflict Data Program (UCDP), Our World in Data, World Bank Fragile States Index.
