# DNA-graph: A Universal Method of Structural Digitization

**Version 2 — expanded edition.**

> Author: **Stig**
> Русская версия: [README.ru.md](README.ru.md)
> DOI: [10.5281/zenodo.21434467](https://doi.org/10.5281/zenodo.21434467) (all versions: [10.5281/zenodo.21433999](https://doi.org/10.5281/zenodo.21433999))

---

## 1. Statement of the problem

A universal method for formalizing an arbitrary object — a hypothesis, a process,
a plan, a diagram, a function — into a structural **branching model**: a directed
graph with typed edges.

The precise term is not "digitization" but **structural formalization** (model
extraction): hypotheses and plans are already symbolic. The pipeline:
representation (object → elements + relations) → structure → diagnostics.
Universality is achieved by pushing the differences between object classes into
**edge typing**: the pipeline is one, only the vocabulary of relations changes.
The universal intermediate form is the triad "elements + typed relations + order";
causality, temporality, and hierarchy are not different structures but different
edge labels on one typed directed graph.

Fractals, the power law, and symmetry are not methods of model generation but
**properties** of an already built model, each with a rigorous test: cycles — via
condensation of strongly connected components; symmetry — the automorphism group;
fractality — box-covering; the power law — only by a rigorous statistical test
(Clauset–Shalizi–Newman), not by visual fitting.

## 2. The tomographic setting: reconstruction of a master object

The direction of the pipeline is not the induction "data → model" but
**reconstruction**: there exists a master object M, and the observed branchings
are its slices-projections π₁(M), π₂(M)… The problem is inverse, as in tomography.

Consequences. Verification means checking whether the projections glue together
as views of one M (sheaf gluing; topological data analysis takes its proper place
here — not extraction, but gluing). Invariants are properties of M: a cycle may
manifest itself only upon gluing the slices. M is fundamentally unattainable in
full: the working model = an approximation of M up to the kernel of the
projections, with **explicit blind zones**.

## 3. Stratification of the slices

Five slices of M, isomorphic to a well-known decomposition: (1) the statics of
branching — topology; (2) internal dynamics — flows ON the graph; (3) external
flows — the boundary of an open system; (4) the history of evolution — the
dynamics OF the graph itself; (5) the senior working model — M as a multilayer
temporal network.

The slices are not of equal rank: dynamics does not exist without statics — the
diagram is layered, statics is the base. The "internal/external" boundary is a
modeling choice, not a given: an explicit parameter tested by an agent. A
contracting cycle is the mechanism of crystallization: an attractor of the
dynamics freezes into structure, whence the self-consistency test — the skeleton
(1) is derivable as the set of attractors of the dynamics (2).

## 4. Unfolding: dynamics is the statics of a larger graph

Any process is rendered static by an unfolding: a node = (element × tick of a
partial order), a flow = a directed edge between temporal copies. "Time" is any
partial order: execution for a process, logical entailment for a hypothesis,
priority for a plan. The unfolding is universal for non-physical objects as well.

The price of the unfolding is infinity; symmetry pays that price. An infinite
unfolding becomes finite statics when there is a symmetry group with a finite
quotient:

- shift symmetry → a **cycle** (periodicity);
- scale symmetry → a **fractal generator + rule** (renormalization group);
- symbolic dynamics → a **finite generator graph + traversal rule** (chaos).

The upshot: **dynamics = a finite static generator graph + a traversal rule** —
three regimes of one mechanism. Two dynamics are equivalent if their generators
are conjugate (shift equivalence). The wave/particle dualism dissolves: the
particle = a node, the wave = an orbit of the symmetry — two factors of one
unfolding. The mandatory invariant is the orientation of edges (the arrow of
time).

## 5. Two primitives and the absence of the external

The scheme compresses to two primitives: the **object** and the **work** — two
factorizations of one unfolding (structure = the attractors of the dynamics).
There is no "external" flow: external(k) ≡ internal(k+1) at the boundary of a
module — it is a higher scale at which the work of the whole becomes a node of
the level above. Fractality becomes architecture: a self-similar tower of
(object, work) pairs connected by a scale operator.

The criterion for an admissible scale step is **lumpability**: the quotient of
the dynamics = the dynamics of the quotient; a non-commuting partition "cuts
through living flesh". The check "resembles the data" is replaced by the check
"the floors commute". The external does not vanish — it is pushed to the top of
the tower (a horizon with boundary conditions). The power law acquires
predictive status: under self-similarity the distribution of module sizes is
bound to be a power law — this is the test of the tower's self-similarity.

## 6. The DNA-graph: a universal structural alphabet

**The DNA-graph is a new notion, not biological DNA.** It is a universal alphabet
of structural primitives from which all real structures are assembled by
composition.

The differentiation of structures (the notional "cell" and "organ" of a project)
is **compositional, not expressional**: one alphabet, different words. The
question "if the DNA is one, where does the difference between organs come from"
does not arise — the difference is in the assembly, not in the reading of the
code.

Mathematically, the alphabet is the set of graphs **indecomposable** with respect
to a chosen composition operation ⊗. The exact analogue of the mechanism is
voltage graphs (Gross–Tucker): a small base + group labels generate a covering of
arbitrary size; the storage key is the canonical form. The canonicity condition
(the "halls of god" — a single foundation rather than one basis among many): ⊗
admits a **unique** decomposition into primes — then the alphabet is not assigned
but **discovered**, it is forced by the operation. For the Cartesian product of
graphs uniqueness is proven (Sabidussi–Vizing); the candidate closest to the
"cell → organ" nesting is **modular composition** (substitution of a subgraph
into a vertex) with its unique canonical modular decomposition tree: the
DNA-graph = the primitive leaves of that tree.

The saving of computation (FLOPs) comes from three sources: invariants (spectrum,
automorphism group, homology, attractors) are computed per class rather than per
instance; symmetry divides the search by a factor of |Aut|; self-similarity
reuses templates across all scales. The power law predicts where the gain lies:
the heavy head of a few templates covers the bulk of structures. A caveat:
orientation breaks the symmetry of the base (Aut of the directed ≤ Aut of the
undirected) — template invariants are upper bounds flagged "needs check". The
size of the base graph is bounded from above: large structures are compositions
of small ones, not new large templates ("codons are few, proteins are many").

## 7. The cell: closing the production loop

The limit of growth of a structural unit is suggested by nature, and it is not
the molecule but the **cell**. A molecule is held together from outside (by bond
energy); a cell holds itself from inside — it maintains its own boundary by
active work. This is operational closure (the autopoiesis of Maturana–Varela; in
graph terms, Rosen's (M,R)-systems).

Formally: the loop **DNA → work → DNA** is closed — the work produces the object,
the object carries the work. This loop closes Rosen's regress ("who repairs the
repairer") in the only possible way: the code encodes the machine that reads the
code; the base template is self-referential. Consequences: the atom of the base
is not merely a subgraph but a **fixed point** of the mapping work → structure →
work (the filter discards stable but dead structures: a crystal is compact but
does not produce itself); the mutual similarity of object and work ceases to be
a hypothesis — it is constitutive of the cell. The practical resolution of the
computational difficulty: a cheap constructor + a strict filter of the living.

## 8. Three levels: code, process, field

Three levels of organization are three mathematical regimes, not three sizes:

- **DNA-graph** — code: generation and storage (combinatorial group theory);
- **cell** — process: self-maintenance, the fixed point of the loop (dynamical
  systems);
- **life** — field: interaction and selection of models in a shared knowledge
  base (ecology, game theory on a network of models).

The transitions are substantive: DNA → cell = unfolding + animation (most
unfoldings do not self-maintain); cell → life = opening of the boundary (the
external of the cell = the internal of the field). Each transition carries its
own selection criterion: the code unfolds → the cell self-maintains → the model
survives among others. The method is self-referential: it is itself DNA (the
method) → cells (the models) → life (the knowledge field).

## 9. Verification

The model is verified by an agent not by fitting to data but by internal
consistency:

1. the orientation of edges is preserved (the arrow of time);
2. the floors commute — the quotient of the dynamics = the dynamics of the
   quotient (lumpability);
3. the skeleton of the statics is derivable as the set of attractors of the
   dynamics;
4. the symmetries are stable under bootstrap resampling (persistence);
5. the distribution of module sizes is a power law (a rigorous test, not a
   visual one);
6. the production loop DNA → work → DNA is closed.

## 10. The open problem

The most fragile point, which must be closed before any code, is **the choice of
the composition operation ⊗**. Until it is chosen, the canonicity of the single
alphabet (the "halls of god") is not a theorem but a requirement. The primitives
are secondary: they follow from the operation.

---

## License

"DNA-graph: A Universal Method of Structural Digitization" © 2026 Stig
is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

You are free to copy, redistribute, adapt, and use the material for any purpose,
including commercially, provided you give appropriate credit.

Full license text: <https://creativecommons.org/licenses/by/4.0/>

**Attribution (example):**

> Based on "DNA-graph: A Universal Method of Structural Digitization"
> © Stig, licensed under CC BY 4.0.
