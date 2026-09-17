# Erdős–Graham #203 — Kummer obstruction paper series

A collection of **nineteen LaTeX manuscripts and eighteen compiled PDFs** on subgroup obstructions, Kummer-character structure, conductor growth, synchronization defects, and the analytic distribution problem arising in Erdős–Graham #203.

The paper-by-paper index is [`papers/PAPERS-INDEX.md`](papers/PAPERS-INDEX.md).

## Mathematical spine

The series develops the problem in four layers.

### Finite subgroup calculus

The early papers establish exact finite-group identities for obstruction sets, including character expansions, moment formulas, CRT synchronization, and local density calculations.

The subgroup-calculus core is also extracted in [`erdos203-obstruction-calculus`](https://github.com/jaredwilder/erdos203-obstruction-calculus).

### Kummer and conductor structure

The middle papers develop:

- conductor identities;
- descent criteria;
- Kummer-character independence;
- synchronization and lifting defects;
- cross-field conductor growth;
- family-averaging and Iwasawa-style decoupling.

These convert the original obstruction problem into a distribution question about structured Kummer data.

### Exact local density

A companion note proves the Gamma-fibre identity

\[
|B_q(c)|=\gcd(a_q,b_q)\,\mathbf 1_{\Gamma_q}(c).
\]

Thus a reachable target occupies density

\[
1/|\Gamma_q|
\]

in one exponent period. This exact local density is the correct starting point for any sieve argument built on the same fibres.

See [`docs/TECHNICAL-COMPANION-NOTES.md`](docs/TECHNICAL-COMPANION-NOTES.md).

### Analytic distribution criterion

The final route isolates a sharp transition near

\[
\ell\log\ell\asymp\log Q
\]

and formulates the remaining non-concentration/distribution input needed to complete that approach.

The series distinguishes unconditional algebraic results from conditional analytic implications. Paper 5 is devoted specifically to why several standard tools—fixed-field Chebotarev, generic Brun–Titchmarsh/Chebotarev bounds, order estimates, and additive-combinatorial routes—do not by themselves supply the required distribution strength.

## Selected papers

### Paper 1 — subgroup obstruction calculus

Finite abelian-group obstruction identities, exact local structure, and the base algebra used throughout the series.

### Paper 5 — analytic route barriers

A systematic comparison of candidate analytic tools against the quantitative distribution statement the #203 route actually requires.

### Paper 16 — conductor and descent structure

Develops the conductor identity, descent emptiness, Iwasawa decoupling, family-averaging dilution, and a Spiegelungssatz bridge.

### Paper 17 — sharp dichotomy

Combines the conductor-growth and non-generation machinery into the `ℓ log ℓ ~ log Q` transition analysis.

## Recovered companion manuscripts

Additional TeX sources include:

- the program dependency map;
- **Exact Gamma-Fiber Local Density and the Kummer-Character Remainder**;
- **A Jet-Primitive Stepanov Auxiliary Theorem for the (2,3)-Orbit**;
- five analytic-route manuscripts recovered from an older source bundle.

Their locations and relationships are indexed in [`docs/TECHNICAL-COMPANION-NOTES.md`](docs/TECHNICAL-COMPANION-NOTES.md) and [`docs/RECOVERED-ANALYTIC-ROUTE.md`](docs/RECOVERED-ANALYTIC-ROUTE.md).

## Related repositories

- [`erdos203`](https://github.com/jaredwilder/erdos203) — finite prime-fibre obstruction and exact covering calculations;
- [`erdos203-obstruction-calculus`](https://github.com/jaredwilder/erdos203-obstruction-calculus) — finite subgroup/Kummer theorem package and verification;
- this repository — the complete manuscript series and companion notes.

## Publication status

These are research manuscripts and supporting notes; repository inclusion does not imply journal publication or peer review. Each paper states its own hypotheses and dependencies.

Author: Jared Wilder. License: Apache-2.0.
