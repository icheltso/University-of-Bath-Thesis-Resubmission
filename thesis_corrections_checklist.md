# Post-Viva Corrections Checklist

This checklist consolidates **all required corrections** from the external examiner report and the internal examiner corrections form. Each item is written to be *tickable* and actionable.

---
🟢 - Finished
🟡 - In progress


## General / Global Revisions
- [🟡] Create a **glossary** of notation used throughout the dissertation.
- [ ] Rewrite **Chapter 4** (Background on stochastics) for clarity and coherence (see detailed comments below).
- [ ] Add a **final conclusions chapter** summarising contributions and future research directions.

---

## Chapter 1
- [🟢] p.12, Eq. (1.1): Make RHS notation consistent (e.g. remove reference to $u_i$).
- [🟡] p.19, l.2–3: Add missing punctuation.
- [🟡] p.20, l.2: Replace `prox?` with `prox_{\omega g}`.
- [🟢] p.21, l.10: Avoid shorthand symbols (→, ↑); spell out prose equivalents throughout.
- [🟢] p.22, l.-9: Correct phrasing: "As such, the related…".
- [🟢] p.24, l.-3: Define **dual norm**.
- [🟢] p.25, l.-8: Introduce Hadamard product notation (also include in glossary).
- [🟢] p.19: Eq. (1.17) should depend on $\lambda$.

---

## Chapter 2
- [ ] p.26, l.-4: Reintroduce reference to Eq. (1.3).
- [ ] p.26, l.8: Clarify meaning of "the choice" (optimal? estimated?).
- [ ] p.26, l.11–12: Explicitly state outer vs inner problem (Eqs. (2.2) and (2.3)).
- [ ] p.26, l.-3: Fix phrasing: "constraints given by the optimality…".
- [ ] p.27, l.-9: Fix arrow notation inconsistency.
- [ ] p.27, l.-7: Expand explanation of Figure 2.2; fix truncated plot.
- [ ] p.27, l.-12: Clarify definition of function $\ell$.
- [ ] p.29, l.-10: Remove duplicated word "both".
- [ ] p.32, l.1–7: Reorder assumptions; define $C$ and $F$; clarify Lipschitz properties.
- [ ] p.32, l.13: Fix wording re differentiation w.r.t. $\omega$.
- [ ] p.33, l.11–12: Quantify "high enough accuracy" and "close enough".
- [ ] p.33, l.16 & p.42, l.10: Fix Algorithm numbering.
- [ ] p.34, l.7: Define parameter $m$.
- [ ] p.38, l.6 & 9: Standardise naming of subroutines.
- [ ] p.42, l.2: Split long equation (e.g. using `multline`).

---

## Chapter 3
- [ ] Explain the **significance of detailed balance** for ergodic Markov chains.
- [ ] Add discussion of **ULA and MALA**.

---

## Chapter 4 (Major Rewrite)
- [ ] p.46, l.-4: Use standard stochastic process notation $(W_t)_{t \ge 0}$.
- [ ] p.47, l.3: Clarify martingale statement and filtration.
- [ ] p.48, l.-3: Clarify what Corollary 5.13 guarantees.
- [ ] p.49, l.8: Clarify new Brownian motion, filtration, and probability space.
- [ ] Eq. (4.4): Clarify type of limit.
- [ ] p.49, l.-4–end: Justify relation between Eqs. (4.6) and (4.7).
- [ ] p.50, §4.2.1: Define $d$, $n$, time domain, and initial conditions.
- [ ] p.51, l.1: Note Eq. (4.16) follows from Eq. (4.6).
- [ ] p.51, l.-1: Fix typo in $W_t$ and state time domain.
- [ ] p.52, l.1: Fix typo in "The forward equation".
- [ ] p.53, l.7: Introduce $\varepsilon$.
- [ ] p.55, §4.4.2: Add sources.
- [ ] p.61, l.-9: Correct definition of $(x_t)_{t\ge0}$.
- [ ] p.61, l.-1: Clarify strong vs weak approximation.
- [ ] p.62, l.3: Define $\vartheta$.
- [ ] p.63, l.-1: Explain $F$ notation (avoid clash with filtrations).
- [ ] p.64, l.11: State where result was shown.
- [ ] p.64, l.-1: Clarify SDE solved by $x$ and role of $\vartheta$.
- [ ] p.66, l.12: (4.4.12) is an Assumption, not an equation.
- [ ] p.70: Add chapter wrap-up.

---

## Chapter 5
- [ ] p.74, l.6: Define **Huber loss**.
- [ ] p.74, l.13: Fix reference to sampling from (5.5).

---

## Chapter 6 (Substantial Mathematical Clarifications)
- [ ] Thm 6.1.1: Clarify non-explosion argument for mollified SDEs.
- [ ] Thm 6.1.1: Address small-probability arguments when $u_t=0$.
- [ ] Thm 6.1.1: Justify use of comparison principle in [36].
- [ ] p.95: Clarify recursive inequality and expectation bounds.
- [ ] p.129: Fix asymptotic bound involving $\mu$-convergence.
- [ ] Present the $\mu$-convergence bound as a **standalone theorem**.
- [ ] p.77: Improve chapter title.
- [ ] p.77–81: Fully define all SDE components at chapter start.
- [ ] p.78–79: Fix notation inconsistencies and long equations.
- [ ] p.81: Clarify Girsanov argument with explicit explanation.
- [ ] p.91: Clarify norms, constants, and step-size dependence.
- [ ] p.101: Correct Leimkuhler–Matthews method and add citation.

---

## Chapter 7
- [ ] Use distinct font for library names.
- [ ] Fig. 7.2: Increase font size; unify vertical axis; explain pink line.
- [ ] Fig. 7.3: Clarify notation ($\lambda$ vs $\omega$) and "useful dimension".

---

## Chapter 8
- [ ] p.120: Add ⇐ to glossary.
- [ ] p.126: Properly cite Ji et al.
- [ ] p.131: Minor wording fixes.
- [ ] Add explanation of stochastic HOAG sampling in practice.
- [ ] Clarify big-O bounds and harmonic series argument.

---

## Global Typos & Style
- [ ] Capitalisation: Lasso, Cartesian, Gaussian, Neumann.
- [ ] Hyphenation: bilevel, hyperparameters.
- [ ] Fix missing brackets around equations (various pages).
- [ ] Standardise notation and spacing.

---

## Optional / Enhancement Suggestions
- [ ] Analyse Cartesian Hadamard–Langevin SDE.
- [ ] Discuss applicability of recent ULA convergence results.
- [ ] Expand discussion of error types (statistical vs sampling vs numerical).

---

*Use this checklist as your master document while revising. Tick items only once fully addressed in the thesis source.*

