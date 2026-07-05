# Post-Viva Corrections Checklist

This checklist consolidates **all required corrections** from the external examiner report and the internal examiner corrections form.

Note, for a correction, 'p.xx,...' refers to page xx in the old pre-viva thesis. 

---
🟢 - Addressed
🟡 - Partially addressed


## General / Global Revisions
- [🟢] Create a **glossary** of notation used throughout the dissertation.
- [🟢] Rewrite **Chapter 4** (Background on stochastics) for clarity and coherence (see detailed comments below).
- [🟢] Add a **final conclusions chapter** summarising contributions and future research directions.

---

## Chapter 1
- [🟢] p.12, Eq. (1.1): Make RHS notation consistent (e.g. remove reference to $u_i$).
- [🟢] p.19, l.2–3: Add missing punctuation.
- [🟢] p.20, l.2: Replace `prox?` with `prox_{\omega g}`.
- [🟢] p.21, l.10: Avoid shorthand symbols (→, ↑); spell out prose equivalents throughout.
- [🟢] p.22, l.-9: Correct phrasing: "As such, the related…".
- [🟢] p.24, l.-3: Define **dual norm**.
- [🟢] p.25, l.-8: Introduce Hadamard product notation (also include in glossary).
- [🟢] p.19: Eq. (1.17) should depend on $\lambda$.

---

## Chapter 2
- [🟢] p.26, l.-4: Reintroduce reference to Eq. (1.3).
- [🟢] p.26, l.8: Clarify meaning of "the choice" (optimal? estimated?).
- [🟢] p.26, l.11–12: Explicitly state outer vs inner problem (Eqs. (2.2) and (2.3)).
- [🟢] p.26, l.-3: Fix phrasing: "constraints given by the optimality…".
- [🟢] p.27, l.-9: Fix * notation.
- [🟢] p.27, l.-7: Expand explanation of Figure 2.2; fix truncated plot.
- [🟢] p.27, l.-12: Clarify definition of function $\ell$.
- [🟢] p.29, l.-10: Remove duplicated word "both".
- [🟢] p.32, l.1–7: Reorder assumptions; define $C$ and $F$; clarify Lipschitz properties.
- [🟢] p.32, l.13: Fix wording re differentiation w.r.t. $\omega$.
- [🟢] p.33, l.11–12: Quantify "high enough accuracy" and "close enough".
- [🟢] p.33, l.16 & p.42, l.10: Fix Algorithm numbering.
- [🟢] p.34, l.7: Define parameter $m$.
- [🟢] p.38, l.6 & 9: Standardise naming of subroutines.
- [🟢] p.42, l.2: Split long equation (e.g. using `multline`).

---

## Chapter 3
- [🟢] Explain the **significance of detailed balance** for ergodic Markov chains.
- [🟢] Add discussion of **ULA and MALA**.
- [🟢] p.43: Clarify what is meant by “posterior distribution difficult to compute”.
- [🟢] p.44: Explain difference between discrete and continuous-state Markov chains.

---

## Chapter 4 (Major Rewrite)
- [🟢] p.46, l.-4: Use standard stochastic process notation $(W_t)_{t \ge 0}$.
- [🟢] p.47, l.3: Clarify martingale statement and filtration.
- [🟢] p.48, l.-3: Clarify what Corollary 5.13 guarantees.
- [🟢] p.49, l.8: Clarify new Brownian motion, filtration, and probability space.
- [🟢] Eq. (4.4): Clarify type of limit.
- [🟢] p.49, l.-4–end: Justify relation between Eqs. (4.6) and (4.7).
- [🟢] p.50, §4.2.1: Define $d$, $n$, time domain, and initial conditions.
- [🟢] p.51, l.1: Note Eq. (4.16) follows from Eq. (4.6).
- [🟢] p.51, l.-1: Fix typo in $W_t$ and state time domain.
- [🟢] p.52, l.1: Fix typo in "The forward equation".
- [🟢] p.53, l.7: Introduce $\varepsilon$.
- [🟢] p.55, §4.4.2: Add sources.
- [🟢] p.61, l.-9: Correct definition of $(x_t)_{t\ge0}$.
- [🟢] p.61, l.-1: Clarify strong vs weak approximation.
- [🟢] p.62, l.3: Define $\vartheta$.
- [🟢] p.63, l.-1: Explain $F$ notation (avoid clash with filtrations).
- [🟢] p.64, l.11: State where result was shown.
- [🟢] p.64, l.-1: Clarify SDE solved by $x$ and role of $\vartheta$.
- [🟢] p.66, l.12: (4.4.12) is an Assumption, not an equation.
- [🟢] p.70: Add chapter wrap-up.

---

## Chapter 5
- [🟢] p.74, l.6: Define **Huber loss**.
- [🟢] p.74, l.13: Fix reference to sampling from (5.5).
- [🟢] p.75: Capitalise **Lasso**.
- [🟢] p.75: Add citation for claim that proximal-based Langevin methods are “go-to” sampling methods.
- [🟢] p.76: Change “not preserved under smoothing” → “not generally preserved under smoothing”.
- [🟢] Fix “cartesian” → “Cartesian”.

---

## Chapter 6 & 7 (Substantial Mathematical Clarifications)
## Major mathematical issues
- [🟢] Thm 6.1.1: Clarify non-explosion argument for mollified SDEs.
- [🟢] Thm 6.1.1: Address small-probability arguments when $u_t = 0$.
- [🟢] Thm 6.1.1: Justify comparison principle from [36].
- [🟢] p.95: Clarify recursive inequality and expectation bounds.
- [🟢] p.129: Fix asymptotic bound involving $\mu$-convergence.
- [🟢] Present $\mu$-convergence bound as standalone theorem.
- [🟢] Expand discussion of error types

## Chapter 6
## Structural / conceptual fixes
- [🟢] p.77: Improve chapter title.
- [🟢] p.77–81: Fully define all SDE components.
- [🟢] p.77–78: State dimensions and independence of Brownian motions.
- [🟢] p.77–78: Promote result “(6.3) gives (6.1)” to its own theorem.
- [🟢] p.78–79: Fix notation inconsistencies and long equations.
- [🟢] p.79: Introduce processes $W^{3,y}_t$, $W^{3,z}_t$.
- [🟢] p.80: Add equation reference for $u_t$.
- [🟢] p.81: Clarify Girsanov argument with explanation of change of measure.
- [🟢] p.81: Ensure time arguments appear consistently.
- [🟢] p.81: Clarify where condition $\rho < \varpi_\omega$ is imposed.

## Technical notation corrections
- [🟢] p.80: Replace $z_t$ with $\hat z_t$ where required.
- [🟢] p.81: Replace $z_t, v_t$ with $\hat z_t, \hat v_t$ where appropriate.
- [🟢] p.82: Fix $1/u_{1,t}^r \to 1/u_{i,t}^r$.
- [🟢] p.85: Fix wording of conjugate exponent sentence.
- [🟢] p.85: Replace “> Δ” with “≥ Δ”.
- [🟢] p.89: Verify correct indexing ($v_k$ vs $v_{k+1}$).
- [🟢] p.91: Clarify norms and constants; check factors of 2 and squares.
- [🟢] p.92: Elaborate uniform bound assumption
- [🟢] p.92–93: Replace references with “Corollary/Proposition …”.
- [🟢] p.93: Fix singular/plural “assumption(s)”.
- [🟢] p.94: Clarify equality vs inequality.
- [🟢] p.97: Replace “(6.2.4)” with “Assumption 6.2.4”.
- [🟢] p.98: Clarify meaning of “sublinearity”.
- [🟢] p.99: Fix wording “and” → “but”.

## Additional clarifications
- [🟢] p.85: Remove odd whitespace.
- [🟢] p.100: Clarify meaning of “unstable”.
- [🟢] p.101: Fix Leimkuhler–Matthews method and add proper citation.
- [🟢] p.101: Replace informal language (“works pretty well”).

---

# Chapter 7
- [🟢] p.102: Restate optimisation problem for clarity.
- [🟢] Ensure correct font usage for library names.
- [🟢] Improve Figure 7.2 (font size, axis consistency, explanation).
- [🟢] Improve Figure 7.3 (notation clarity).
- [🟢] Add discussion on **error metrics vs predictive accuracy**.

---

# Chapter 8
- [🟢] p.119: Elaborate on sample choice in practice.
- [🟢] p.120: Add to glossary.
- [🟢] p.121: State that proofs are in Appendix C.
- [🟢] p.123–125: Fix whitespace gaps.
- [🟢] p.126: Properly cite Ji et al.
- [🟢] p.126: Clarify $O(1/\zeta - 1/(\zeta K^\zeta))$ bound.
- [🟢] p.126: Clarify whether expectation is needed in gradient norm.
- [🟢] p.126: Clarify modularity claim regarding stoc-HOAG.
- [🟢] p.128: Clarify interpretation of $\mu$.
- [🟢] p.130: Fix capitalisation (Neumann, Gaussian).
- [🟢] p.131: Minor wording fixes.

---

## Global Typos & Style
- [🟢] Capitalisation: Lasso, Cartesian, Gaussian, Neumann.
- [🟢] Hyphenation: bilevel, hyperparameters.
- [🟢] Fix missing brackets around equations (various pages).
- [🟢] Standardise notation and spacing.

---


## Extra points from start of IE report (I began from EE report so missed these initially)
- [🟢] p.3: Add citations supporting introductory claims about Langevin methods and sparsity.
- [🟢] p.9: Clarify that convergence result requires the additional assumption discussed later.
- [🟢] p.21: Fix spacing: `|x|for` → `|x| for`.
- [🟢] p.24: Replace `R^+_d` with `\mathbb{R}^+_d`.
- [🟢] p.35: Use `hyperparameters` (not `hyper-parameters`).
- [🟢] p.37: Correct reference `(8.4)` → `(2.18)`.
- [🟢] p.38: Correct reference `(8.2)` → `(2.19)`.
- [🟢] p.49: Explain what `\tilde P_T` is and its relation to the exponential martingale.
- [🟢] p.49: Add brackets around expectation in Eq. (4.5).
- [🟢] p.57: Replace `\nabla^2V \ge RI_d` with `\nabla^2V \succeq RI_d`.
- [🟢] p.66: Define $\hat\varphi_{N_{iter},\Delta t}$ and specify ranges of $n,m$ in (4.45).
- [🟢] p.89: Verify whether logarithm should use $u_k$ or $u_{k+1}$.
- [🟢] p.91: Clarify whether constants in Theorem 6.2.3 depend on the timestep.
- [🟢] p.101: Remove the double noise coefficient in Leimkuhler–Matthews method.
- [🟢] p.141: Replace $x_i^2/\eta$ with $x_i^2/\eta_i$.
- [🟢] p.144: Change to $B=\mathbb E[\tilde B]$

## Optional / Enhancement Suggestions
- [🟡] Analyse Cartesian Hadamard–Langevin SDE. -> Future work.
- [🟢] p.35 Change `\hat{x}(\lambda_k)` to `x_k`
- [🟢] p.36: Change `Id y_k` to `y_k`
- [🟢] p.122: Align `=` with `\leq`
- [🟢] p.130: Mention other implicit schemes for neumann ode.
- [🟢] p.130: Explain use of Woodbury identity.


---

*Use this checklist as your master document while revising. Tick items only once fully addressed in the thesis source.*

