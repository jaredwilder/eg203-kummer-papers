# EG203 technical companion notes and program roadmap

**Author:** Jared Wilder  
**Recovered into the public estate:** 2026-09-11

Three substantial TeX sources were released from an old generic `notes/` directory in `jaredwilder/unpublished-math-papers`. They belong mathematically to this EG203/Kummer paper series and are indexed here so readers do not need to discover them by archive archaeology.

The original bytes remain in the provenance archive; this page is their **canonical navigation surface**.

## 1. Program overview

Archive source:

`jaredwilder/unpublished-math-papers/notes/PROGRAM_OVERVIEW.tex`

Title:

**A Research Program for Erdős–Graham Problem #203: Algebraic Structure, Conditional Routes, and the High-l Analytic Seam**

This is the roadmap for the multi-manuscript program. It separates:

- unconditional finite-group / Kummer / CRT / Fourier / matroid mathematics;
- conditional analytic criteria;
- rejected routes;
- the high-`l` non-concentration problem left open by the program.

Among the unconditional items catalogued there are exact local-density and moment identities, squarefree synchronization criteria, Kummer slope/collision structure, CRT independence, Poisson-binomial obstruction laws, Kummer log matroids, generalized Wieferich lifting, finite Fourier collision energy, rank-`r` Kummer geometry, cut-gap bounds, row-balance results at fixed `l`, exact large-sieve/fiber identities and several negative theorems that delimit insufficient analytic routes.

The overview does **not** claim to close EG203; it is valuable precisely because it gives the reader the dependency graph and separates the proved algebra from the open analytic seam.

## 2. Exact Gamma-fiber local density

Archive source:

`jaredwilder/unpublished-math-papers/notes/exact_gamma_fiber_local_density.tex`

Title:

**Exact Gamma-Fiber Local Density and the Kummer-Character Remainder for `m*2^k*3^l+1`**

Its central exact identity is:

`|B_q(c)| = gcd(a_q,b_q) * 1_{Gamma_q}(c)`,

where `a_q=ord_q(2)`, `b_q=ord_q(3)`, and `Gamma_q=<2,3> mod q`.

Equivalently, because

`|Gamma_q| = lcm(a_q,b_q) = a_q b_q / gcd(a_q,b_q)`,

a reachable residue occupies exact density

`1 / |Gamma_q|`

in one exponent period. The note then rewrites local divisibility density as a uniform term plus a Kummer-character discrepancy and develops the resulting analytic remainder.

This note is an important exact algebraic interface for the program and supersedes a weaker Stepanov bound for the specific EG203 fiber-counting question.

## 3. Jet-primitive Stepanov auxiliary theorem

Archive source:

`jaredwilder/unpublished-math-papers/notes/stepanov_auxiliary_theorem.tex`

Title:

**A Jet-Primitive Stepanov Auxiliary Theorem for the (2,3)-Orbit**

This note develops an auxiliary-polynomial construction for the two-parameter multiplicative orbit, with a degree bound of the form

`D = O(h_q^(1/2) log q)`

outside its stated exceptional set.

For the specific EG203 local fiber, the note explicitly acknowledges that the exact Gamma-fiber identity above is stronger. Its value is methodological: the auxiliary-polynomial construction is intended to transfer to settings in which the orbit is not simply the underlying finite group.

## Relationship to the numbered papers

These three sources are companions to the numbered paper series rather than competing projects:

- the program overview supplies the dependency map;
- the exact Gamma-fiber note supplies a reusable exact local identity used throughout the obstruction calculus;
- the Stepanov note preserves an independent method that is superseded locally but potentially transferable.

The numbered papers, compiled PDFs, and their current status remain indexed by `papers/PAPERS-INDEX.md` and this repository's root README.

## Provenance rule

The archive copies are retained unchanged so release chronology and exact source provenance remain public. Future revisions should occur in the subject-level paper series or in clearly versioned descendants, not by silently rewriting the archival copies.
