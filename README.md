# Exploration of Modeling in Game Theory

**MAT 5450 · Cal Poly Pomona · December 2025**

An introductory exploration of game theory fundamentals, with emphasis on mathematical modeling of strategic interaction and evolutionary dynamics.

---

## Overview

This paper traces a path from the classic Prisoner's Dilemma through pure and mixed strategies, arriving at the Taylor-Jonker replicator dynamic, a continuous ODE system for modeling how strategy distributions evolve over iterated play.

The goal was not comprehensive coverage of game theory (an impossibly broad subject) but a focused, mathematically rigorous first pass at the tools most relevant to modeling cooperative and competitive behavior in complex systems.

---

## Topics Covered

**Prisoner's Dilemma**
- Single-shot game structure and payoff matrices (Flood & Dresher, 1950)
- Nash Equilibrium and why rational actors defect

**Pure Strategies**
- Cooperator vs. Defector
- Cooperator vs. Tit For Tat
- Defector vs. Tit For Tat
- Expected payoff calculations across 25-match iterated games

**Mixed Strategies**
- Notation and expected payoff formula: $U^1(\sigma^1, \sigma^2) = (\sigma^1)^T A \sigma^2$
- Numerical examples with specific strategy probability vectors

**Taylor-Jonker Replicator Dynamic**
- Derivation of the replicator equation from evolutionary biology
- ODE formulation: $\dot{\sigma}^i_h = \sigma^i_h \left( u^i_h(\sigma^j) - \bar{u}^i(\sigma^j) \right)$
- Phase portrait analysis and fixed point behavior
- Weibull example: corroborating Nash Equilibrium via a second payoff matrix

---

## Key Result

Two distinct payoff matrices
* The standard Prisoner's Dilemma
* Weibull's symmetric example
They produce equivalent vector fields under their respective replicator dynamics, with fixed points at 0 (stable) and 1 (unstable). This computationally corroborates Nash Equilibrium theory.

---

## Tools

- LaTeX (typesetting and mathematical notation)
- Python (payoff calculations and phase portrait plotting)

---

## References

- Von Neumann & Morgenstern, *Theory of Games and Economic Behavior* (1944)
- Flood, "Some Experimental Games," *Management Science* (1958)
- Taylor & Jonker, "Evolutionary Stable Strategies and Game Dynamics," *Mathematical Biosciences* (1978)
- Hofbauer & Sigmund, *Evolutionary Games and Population Dynamics* (1998)
- Weibull, *Evolutionary Game Theory* (1997)
- Cressman & Tao, "The Replicator Equation and Other Game Dynamics," *PNAS* (2014)

---

## Notes

This work constitutes a deliberate first step into game theory, with clear directions for future study: higher-dimensional strategy spaces, multiplayer games, fixed point stability analysis, and connections to complexity economics and policy modeling.

*Grammar and formatting assisted by Claude Opus 4.5.*
