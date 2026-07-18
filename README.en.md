# DNA-graph: A Universal Method of Structural Digitization

> Working title. Concept document fixed for publication.
> Author: **Stigriosan**
> Русская версия: [README.md](README.md)
> DOI: [10.5281/zenodo.21434000](https://doi.org/10.5281/zenodo.21434000)

---

## Core idea

A universal method for formalizing an arbitrary object — a hypothesis, a process,
a plan, a diagram, a function — into a structural **branching model** (a directed
graph with typed edges). One pipeline for all classes of objects: the differences
between classes are moved into edge semantics, not into the architecture of the
method.

The method rests on three propositions.

### 1. Unfolding: dynamics is the statics of a larger graph

Any process is rendered static through an unfolding: a node = (element × tick of
a partial order), a flow = a directed edge between temporal copies. "Time" is any
partial order: for a process — execution, for a hypothesis — logical entailment,
for a plan — priority.

An infinite unfolding becomes finite statics precisely when it has a symmetry
group whose quotient is finite:

- shift symmetry → a **cycle** (periodicity);
- scale symmetry → a **fractal generator + rule** (renormalization group);
- symbolic dynamics → a **finite generator graph + traversal rule** (chaos).

The upshot: **dynamics = a finite static generator graph + a traversal rule.**
The object and its work are two factorizations of one unfolding (structure = the
attractors of the dynamics). There is no "external" flow: it is merely a higher
scale at which the work of the whole becomes a node of the level above. Hence a
self-similar tower of (object, work) pairs connected by a scale operator.

### 2. The DNA-graph: a universal structural alphabet

**The DNA-graph is a new notion, not biological DNA.** It is a universal alphabet
of structural primitives from which all real structures are assembled by
composition. Different structures (the notional "cell" and "organ" of a project)
differ **compositionally** — like different words built from the same letters —
not by different readings of one code.

The alphabet is defined as the set of graphs **indecomposable** with respect to a
chosen composition operation ⊗. If ⊗ admits a unique decomposition into primes
(e.g., modular decomposition with its canonical tree), the alphabet is not
assigned but **discovered** — it is forced by the operation and is canonical.
This is the "halls of god": a single foundation rather than one basis among many.

A real directed graph is then not stored in full — what is stored is a reference
to the base plus an assembly pattern. Invariants (spectrum, automorphism group,
homology, attractors) are computed once per class rather than per instance. The
goal is a **drastic reduction of computational cost (FLOPs)** through
dictionary-based reuse of templates across all scales.

### 3. The cell and the three levels

The unit of the tower is the **cell**: the minimal structure in which the loop of
production closes on its own code (DNA → work → DNA). This loop closes the repair
regress ("who repairs the repairer") — the base template is self-referential.
Three levels of organization:

- **DNA-graph** — code (generation, storage);
- **cell** — process (operational closure, self-maintenance);
- **life** — field (interaction and selection of models in a shared knowledge
  base).

Each transition carries its own selection criterion: unfoldability →
self-maintenance → survival among other models.

### Verification

The model is verified by an agent not by fitting to data but by internal
consistency: preservation of orientation (the arrow of time), **commutativity of
the floors** (the quotient of the dynamics = the dynamics of the quotient),
**stability under resampling** (persistence), and a **power law** in the
distribution of module sizes as a test of the tower's self-similarity.

---

## License

"DNA-graph: A Universal Method of Structural Digitization" © 2026 Stigriosan
is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

You are free to copy, redistribute, adapt, and use the material for any purpose,
including commercially, provided you give appropriate credit.

Full license text: <https://creativecommons.org/licenses/by/4.0/>

**Attribution (example):**

> Based on "DNA-graph: A Universal Method of Structural Digitization"
> © Stigriosan, licensed under CC BY 4.0.
