# LANE 2 — THE STAIRCASE: Toy Build Report
**Built 2026-10-24 on Jeff's "full send." Tier: numerical exploration (T4-grade). Verdict: C1 PASS · C2 PASS · kills unfired (K3 at ordering level) — a universality exhibit, capped by charter. NO CLAIM.**
Design of record: `devils-staircase-toy-design-2026-10-24.md` (frozen before the build; claim, null, and kills as registered there — denominator rule applied exactly as the registered kill states: q ≤ 5).

## Column 1 — the model staircase (circle map, K = 1, computed)
Plateau widths in Ω, rationals with q ≤ 5 (grid 4001, winding number by long iteration):
1/1: **0.159** · 1/2: **0.0735** · 1/3, 2/3: **0.0302** · 1/4, 3/4: **0.0158** · fifths: **0.009–0.010**.
The Farey ordering is reproduced exactly: the wider the tongue, the lower the rational's order. This column is known mathematics, computed here as the diagram's spine — claimed as reproduction, not discovery.

## Column 2 — the chains (C1)
Best q ≤ 5 rational and relative distance ε for every adjacent pair (periods: NASA/JPL fact sheets; TRAPPIST-1 per Agol et al. 2021):
Europa/Io 2.0073 → 2/1, ε **0.36%** · Ganymede/Europa 2.0147 → 2/1, ε **0.73%** · T-1 c/b 1.6031 → 8/5, ε **0.19%** · d/c 1.6719 → 5/3, ε **0.31%** · e/d 1.5067 → 3/2, ε **0.45%** · f/e 1.5090 → 3/2, ε **0.60%** · g/f 1.3417 → 4/3, ε **0.63%** · h/g 1.5193 → 3/2, ε **1.29%**.
**All 8 pairs sit within 1.29% of a wide-tongue rational. C1 PASSES as registered** — no pair dropped, no depth added (K1, K2 unfired).

## Column 3 — the null (C2) and the control
Solar-system adjacent pairs, same ruler: Mercury–Venus ε 1.76% · Venus–Earth 1.60% · Earth–Mars 4.49% · Mars–Jupiter 0.42% (19/3 — a wide-ratio artifact of the q ≤ 5 net, printed, not hidden) · Jupiter–Saturn 0.67% (5/2 — the genuine historical near-commensurability of the Great Inequality) · Saturn–Uranus 1.87% · Uranus–Neptune 1.95%.
Pass rates by tolerance — chains vs null: **0.5% → 4/8 vs 1/7 · 1.0% → 7/8 vs 2/7 · 1.5% → 8/8 vs 2/7 · 2.0% → 8/8 vs 6/7.** The discrimination is real at tight tolerance and washes out at 2% — the method's boundary, printed on the exhibit. **C2 PASSES** (null distinguishable; K4 unfired).
*Control (K3, ordering level):* Josephson Shapiro steps sit on the same ordering in the literature — step widths decrease with denominator order — represented qualitatively; no width numbers were fabricated for the overlay. K3 discharged at the ordering level only, and the report says so.
*Diagnostic (not scored):* Callisto/Ganymede = 2.3326 sits **0.03%** from 7/3 and is not a librating chain pair. Proximity is cheap; libration is the real criterion — the toy measures occupation ordering, nothing more, and its own diagnostic row proves why that modesty is required.

## Verdict and cap
The staircase's measure orders the two real chains' occupations, against a null that mostly fails the same ruler. Small samples (8 vs 7 pairs) — stated, not laundered. By charter this is **a universality exhibit**: mode-locking mathematics describes where these systems live. It is not evidence for any identity between moons and quantum systems, it moves no dial, and it is filed beside Lane 3's 10⁷⁰ as the bridge's second honest measurement: *the pattern is real; the pattern is not the thing.*
Script: `routeb-general-scratch/devils_staircase.py`; raw results: `routeb-general-scratch/staircase_results.json`.
