# LANE 2 — THE STAIRCASE: Devil's-Staircase Toy, Design
**Bridge artifact, 2026-10-24. Tier: design (T4 mathematics; unbuilt toy). Priced: this design S — build M, only on Jeff's further word. NO CLAIM.**

## The one diagram
Plot, on one winding-number axis, three substrates that share nothing but the mathematics of mode-locking:
1. **The model (computed):** the dissipative circle map θ → θ + Ω − (K/2π)·sin(2πθ) at criticality K = 1: plateaus at every rational p/q, widths ordered by the Farey tree (mediants between neighbors; low-order rationals widest), the unlocked remainder a Cantor set of fractal dimension ≈ 0.87 (the universality the toy is allowed to admire but not to "discover" — it is known mathematics).
2. **The planetary chains (measured):** adjacent period ratios of the Galilean chain (Europa/Io ≈ 2.007, Ganymede/Europa ≈ 2.015 — near 2:1, librating) and TRAPPIST-1's six adjacent ratios (≈ 1.603, 1.672, 1.506, 1.509, 1.342, 1.519 — near 8:5, 5:3, 3:2, 3:2, 4:3, 3:2, with its three-body Laplace-like relations), placed against the Farey ordering of the rationals they neighbor.
3. **The laboratory control (literature values):** Josephson-junction Shapiro step widths — the same staircase measured on a bench, where the theory is not in dispute. The control exists so the diagram has one column nobody can argue with.

## The registered claim (written before any build)
**C1:** In both planetary chains, every adjacent pair's period ratio neighbors a rational whose Farey order (denominator, at tree depth ≤ 4) is low — i.e., occupied resonances are drawn from the staircase's *wide* tongues, with no occupied pair requiring a denominator > 5 at depth ≤ 4.
**C2 (the null that must also be printed):** the same test run on a matched set of NON-chain multi-planet systems (adjacent pairs with no known resonance) — if they pass C1 at a similar rate, C1 is vacuous and the toy reports exactly that.

## Pre-registered kills (periodic-table discipline)
- **K1 — cherry-pick:** if passing requires dropping a chain member, a pair, or a system after seeing the numbers → NO CORRELATION, filed, no rerun.
- **K2 — depth shopping:** Farey depth is fixed at ≤ 4 in advance (this document). Any analysis needing depth 5+ to pass is a FAIL of C1 as registered.
- **K3 — control failure:** if the Josephson column cannot be reproduced from literature values to sit on the same ordering, the diagram is withdrawn as a drawing, not published as a near-miss.
- **K4 — vacuity:** C2's null rate within noise of the chains' rate → verdict NO CORRELATION at full rank.
A pass is capped by charter: **a universality exhibit** — evidence that mode-locking's mathematics describes these occupations (already believed on other grounds), never evidence for the dropped document's identity claims, and never a dial-mover.

## Build spec (when commissioned)
Python, one script: (i) circle-map staircase by bisection on Ω for rationals to depth ≤ 4, plateau widths tabulated; (ii) chain data hard-coded from cited sources (JPL/NASA fact sheets for the Galilean periods; published TRAPPIST-1 ephemerides, e.g. Agol et al. 2021) with the source printed next to every number in the output; (iii) the three-column figure + the C1/C2 scorecard as the only outputs. Estimated effort M (data hygiene dominates: the control column and the null set are the work; the staircase itself is an afternoon).
**Design status: complete and frozen. The toy builds only on Jeff's word.**
