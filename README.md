# The Time Bubble Hypothesis
**A relativistic framework for why advanced civilizations may be common yet temporally unobservable.**

> I model how relativity (time dilation, light‑cone overlap, and cosmological expansion) can prevent overlapping communication windows between civilizations—resolving the Fermi Paradox without assuming rarity or self-destruction.

---

## 🚀 Overview
This repository develops a quantitative, simulation-backed framework for the **Time Bubble Hypothesis**: the idea that civilizations can exist but remain **temporally isolated** from one another due to relativistic effects. We extend the Drake Equation with an **observability term** \(O\) and explore parameter regimes via Monte Carlo and agent-based simulations.

**Core research questions**
- Can relativity alone explain “Great Silence” observations?
- How does a relativistic **observability** factor modify Drake-style predictions?
- In which parameter regimes (lifespan, distance, velocity, expansion) is cross-civilization contact effectively impossible?

---

## 📐 Formal Sketch
I introduce an observability factor **O** capturing the probability that two civilizations’ **communication windows overlap** in relativistic spacetime.

$$
N = R_* \cdot f_p \cdot n_e \cdot f_l \cdot f_i \cdot f_c \cdot L \cdot O
$$


**Key determinants of \(O\):**
- **Light-cone overlap:** causal contact given spacetime separation.
- **Relative velocity \(v\):** time dilation \(\gamma = 1/\sqrt{1 - v^2/c^2}\).
- **Cosmology:** expansion rate \(H_0\), redshift \(z\), comoving distance.
- **Civilization lifespan \(L\):** finite windows for emission/detection.

_(Full derivations and numerical estimators for \(O\) will be developed in `/paper/` and `/src/model/`.)_

---

## 🧪 Planned Simulations
- **Monte Carlo (MC):** Randomly place civilizations in spacetime; draw lifespans, emergence times, and velocities; estimate \(O\) from overlap statistics.
- **Agent-Based (ABM):** Agents (civilizations) evolve clocks and policies (emit/expand/listen); log detectable-contact events under relativity.
- **Sensitivity sweeps:** \(L\), \(v\), emergence rate, detection thresholds, cosmology parameters.

Outputs:
- Detection probability curves vs. distance/redshift.
- Phase diagrams showing “communication impossible” regions.
- Minkowski-style visualizations of non-overlapping windows (“time bubbles”).

---

