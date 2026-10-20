# Eduardo Nava Hernández

Formal physics in Lean 4. Four blocks.

## 1 · Merged & open — Physlib

What passed review in [Physlib](https://github.com/leanprover-community/physlib), the Lean physics library of the community.
[![merged](https://img.shields.io/github/issues-search?query=repo%3Aleanprover-community%2Fphyslib%20is%3Apr%20is%3Amerged%20author%3Anaype888-cloud&label=merged&color=blue)](https://github.com/leanprover-community/physlib/pulls?q=is%3Apr+is%3Amerged+author%3Anaype888-cloud)
[![open](https://img.shields.io/github/issues-search?query=repo%3Aleanprover-community%2Fphyslib%20is%3Apr%20is%3Aopen%20author%3Anaype888-cloud&label=open&color=lightgrey)](https://github.com/leanprover-community/physlib/pulls?q=is%3Apr+is%3Aopen+author%3Anaype888-cloud)

- [Merged pull requests](https://github.com/leanprover-community/physlib/pulls?q=is%3Apr+is%3Amerged+author%3Anaype888-cloud) — the reference
- [Open pull requests](https://github.com/leanprover-community/physlib/pulls?q=is%3Apr+is%3Aopen+author%3Anaype888-cloud)
- Working fork: [`physlib`](https://github.com/naype888-cloud/physlib)

## 2 · NRS³·T³ — the canon

Nava–Robertson–Schrödinger uncertainty on the three-torus `T³`: three closed axes, every state.

- **[`nava-robertson-schrodinger`](https://github.com/naype888-cloud/nava-robertson-schrodinger)** — README and interactive page open on `T³`
- [`nrs3-tritoro`](https://github.com/naype888-cloud/nrs3-tritoro) — the Lean of `T³`, on [`nrs3-hopf`](https://github.com/naype888-cloud/nrs3-hopf)
- Pages on `T³`: [de Sitter](https://naype888-cloud.github.io/nrs3-de-sitter/t3.html) · [SL(2, ℂ) and the cone](https://naype888-cloud.github.io/nrs3-uncertainty-cone/lorentz-t3.html)

## 3 · NRS³ | variations

Everything that is not `T³` stays, each by itself: the open cube, extra axes, and the topics that
grew out of NRS³.

| Repository | In one line |
|---|---|
| [open cube (`NRS_OPEN_CUBE.md`)](https://github.com/naype888-cloud/nava-robertson-schrodinger/blob/main/NRS_OPEN_CUBE.md) | NRS, NRS³, det\|NRS³ on the open cube, `D0`–`D49t` |
| [`nrs3-cristales`](https://github.com/naype888-cloud/nrs3-cristales) | symmetry shapes Σ and Ω; the spectrum gives the size |
| [`nrs3-mandelstam-tamm-cramer-rao`](https://github.com/naype888-cloud/nrs3-mandelstam-tamm-cramer-rao) | time–energy bound and Cramér–Rao |
| [`nrs3-uncertainty-cone`](https://github.com/naype888-cloud/nrs3-uncertainty-cone) | the Gram matrix of a conjugate pair is a Minkowski four-vector |
| [`nrs3-de-sitter`](https://github.com/naype888-cloud/nrs3-de-sitter) | horizon entropy fixes the cosmological constant |
| [`nrs3-dark`](https://github.com/naype888-cloud/nrs3-dark) | `1 − Ω_b`, the interior of the volumetric quantum |
| [`nrs3-landauer-carnot`](https://github.com/naype888-cloud/nrs3-landauer-carnot) | Landauer, Kelvin–Planck, Carnot |
| [`nrs3-pauli-dirac`](https://github.com/naype888-cloud/nrs3-pauli-dirac) | exclusion, shells `2n²`, spin matrices, Dirac |
| [`nrs3-poincare`](https://github.com/naype888-cloud/nrs3-poincare) | Planck's law forces discrete levels |
| [`nrs3-defect-curvature`](https://github.com/naype888-cloud/nrs3-defect-curvature) | non-local links close cycles, one quantum each |
| [`nrs3-penrose`](https://github.com/naype888-cloud/nrs3-penrose) · [`nrs3-rovelli-lqg`](https://github.com/naype888-cloud/nrs3-rovelli-lqg) | proposals, outside NRS³ |

## 4 · BACQM Systems

Linux kernel modules and a `sched_ext` scheduler that cut tail latency (p99, p999, max).
Measured on one machine; no data-center numbers yet. Documentation and modules, first as LaTeX.
*(Repository `bacqm-systems` is local; not published yet.)* — [bacqm.com](https://www.bacqm.com)
