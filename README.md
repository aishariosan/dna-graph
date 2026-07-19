# Universal Structural Digitization of Branchings

**Version 3.**

> Author: **Stig**
> Русская версия: [README.ru.md](README.ru.md)
> DOI: [10.5281/zenodo.21436211](https://doi.org/10.5281/zenodo.21436211) (all versions: [10.5281/zenodo.21433999](https://doi.org/10.5281/zenodo.21433999))
> Updated: 2026-07-19 05:41

---

### graph-units → chain (DNA / RNA) → cell → organ → life

## 1. What it is

A universal method: any object — hypothesis, function, process, plan, scheme — is turned into a branching graph plus the dynamics running on it. One method for all classes; class differences are pushed into relation typing. "Digitization" here is not conversion to numbers but extraction of the hidden graph and its work.

## 2. Core principle: folding, not assembly

The method runs **top-down**. Structure is not built from blocks — it is folded down to an irreducible core:

```
object → project digraph into graph → strip symmetry → strip fractal → CORE
```

The core is the point where reduction halts. It compresses no further.

## 3. graph-unit (core)

The core (graph-unit) is the base building unit, an analog of a DNA base (biology has 4 bases).

**Definition by negation:** an asymmetric spatial figure with no symmetry and no fractality one level below. The logic is exact — symmetry and self-similarity are compressibility; squeeze out everything compressible and an incompressible residue remains. This is algorithmic-information logic: structure = redundancy, core = pure information; the incompressible looks asymmetric by nature.

Cores are **few** — the alphabet is finite. Hypothesis: their count depends on the spatial dimension of the figure — **2, 3, 4** (4 = depth, a fourth axis for 3D; ℝ⁴ is mathematically legitimate though not visualizable). The library of cores is replenished in the course of working by the protocol.

*Status:* the graph-unit itself is still a hypothesis — defined as a computational process that manifests during reduction, not as a pre-given symbol.

## 4. Three decoration axes

The core is form only. A real object dresses the form with three separate axes at assembly:

> **object = chain of cores + directions + parallels + strobe(time)**

- **directions** — causality (edge orientation);
- **parallels** — edge multiplicity;
- **strobe(time)** — a stroboscope: freezes dynamics into a sequence of static frames.

Reduction stripped both time and direction precisely because it stripped *all* decoration to reach the form. Single principle: **alphabet = forms, reality = forms + three decoration axes.**

## 5. Chain and branching (genotype / phenotype)

A chain of cores (1D) is the **code (genotype)**. Branching is what the code unfolds into (the **phenotype**). As in biology: a 1D sequence of bases → a multidimensional folded structure.

Here is the source of compression and FLOPs economy: a tiny alphabet + long chains = unbounded structures. Properties are computed once per core and reused. Nature already proved it — 4 bases generate all of life.

## 6. DNA and RNA

The same cores build both carriers:

- **DNA = structure** — a figure (static, dim 2/3/4);
- **RNA = work** — a strobe-sequence of figures.

This resolves the original thesis "dynamics can be static": each frame is still, motion = the sequence of frames.

## 7. Levels: DNA → cell → organ → life

The levels are **genuinely independent** — not a matryoshka. An organ is assembled directly from cores; knowing the cell's structure is not required (direct action). Cell and organ are different types in one library, not nested layers. Principle: **simplicity = health, complexity = disease.**

- **Cell** — operationally closed: the loop DNA → work → DNA closes onto its own code (resolving the "who repairs the repairer" regress). Distinguishes the living from dead form.
- **Organ** — a larger self-sufficient unit, assembled by *its own* code, not by gluing cells.
- **Life / field** — the environment where models interact and are selected.

## 8. Merge: 1 + 1 = 1

Merging graphs always yields a **new whole**, not a sum (1+1=1; 1+1+1+2=1). Merge = recombination of chains: two chains produce a new one (a new DNA set), not an end-to-end concatenation. The library is **generative** — new cores surface in the course of work, yet remain few.

## 9. Selectivity

Not everything can be digitized: combinatorics beats FLOPs by a power law. Only what interests the researcher is digitized — a cognition mechanism is built per query. The knowledge field is **lazy**: a model exists only if it was requested. (Uncontrolled growth = disease; selectivity = health.)

## 10. Verification by agent

A model is accepted if it passes:

- orientation preserved (causality intact);
- levels commute (coarsening is valid);
- skeleton = attractors of its own work;
- symmetries stable under resampling (signal, not artifact);
- part-size distribution is power-law (self-similarity);
- production loop is closed (living, not a warehouse of forms).

## 11. Status of claims

**Solid:** reduction of dynamics to statics (strobe); the three decoration axes; the DNA/RNA split; economy via a small alphabet; TDA / persistent homology as the tool for finding cores (the first tool named in the project turned out to be the tool for the last layer — the circle closed).

**Bet (held consciously):** asymmetric spatial cores are a finite small number, indexed by dimension 2, 3, 4. There is precedent — finite classifications of irreducibles in geometry (regular polytopes: 3D → 5, 4D → 6). But for the *asymmetric* case there is no off-the-shelf classification; this is the author's hypothesis.

**First concrete step** (the philosophy has reached counting): enumerate the asymmetric irreducible figures in 2D / 3D / 4D — run the reduction on many objects, check whether the residues cluster into a short list indexed by dimension. 4D cores are the one place where intuition fails but homology does not.

**Open parameter:** strobe frequency. A wrong rate → aliasing (false motion from correct frames), and the RNA sequence becomes a sampling artifact. The same coin as the resampling-stability test.

---

## Glossary

- **Digitization** — extraction of the hidden branching graph and its dynamics.
- **graph-unit / core** — an irreducible asymmetric spatial figure; the base unit (analog of a DNA base).
- **Chain** — a 1D sequence of cores; the code (genotype).
- **Branching** — the phenotype folded from the chain.
- **DNA / RNA** — structure (figure) / work (strobe-sequence of figures).
- **Strobe** — stroboscopic sampling of time into static frames.
- **Three decoration axes** — directions (causality), parallels (multiplicity), strobe (time).
- **Cell** — an operationally closed unit (loop DNA → work → DNA).
- **Merge 1+1=1** — recombination of chains into a new whole.

---

*This document is a public disclosure of the concept as of 2026. For terms of use, see LICENSE. Revision 0.2 supersedes the earlier bottom-up description (assembly from bricks); the current foundation is top-down folding to cores.*
