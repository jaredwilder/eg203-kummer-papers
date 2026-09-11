# Erdős–Graham #203 and Kummer obstruction papers

A collection of **nineteen LaTeX sources and eighteen compiled PDFs** from a research program on Erdős–Graham #203, with particular emphasis on Kummer-theoretic non-concentration and conductor/distribution obstructions.

Author: Jared Wilder. First public timestamp: 2026-09-10.

`papers/PAPERS-INDEX.md` contains the paper-by-paper index prepared before release.

## Principal papers

### Paper 17 — sharp dichotomy at `ℓ log ℓ ≍ log Q`

The headline paper isolates a transition at the scale `ℓ log ℓ ≍ log Q` and combines several previously separate ingredients: a conductor-growth mechanism, a no-Siegel-zero component, an Artin-style non-generation input, and cross-field conductor growth.

The historical source uses internal abbreviations such as `JANG`, `CTREX`, and `Artin-NG`; the paper itself defines those objects precisely. The mathematical statement should be read from the theorem section rather than from those abbreviations.

### Paper 16 — conductor/descent/Iwasawa structure

Paper 16 develops five named results:

- Conductor Identity;
- Descent Emptiness;
- Iwasawa Decoupling;
- Family-Averaging Dilution;
- Spiegelungssatz Bridge.

It also contains a Siegel-free zero-free-region argument and a synthesis of the remaining analytic obstructions.

## Structure of the paper series

The corpus contains several different kinds of mathematics:

- unconditional theorem papers;
- algebraic and structural papers;
- conditional analytic criteria isolating the remaining distribution input;
- one paper devoted to approaches that fail at the required strength.

Each paper states its own hypotheses and dependencies, so unconditional and conditional results are not merged into one status.

**Paper 05** is the negative-route analysis. It explains why BFI, Plünnecke–Ruzsa, fixed-field Chebotarev, order bounds, and generic Chebotarev–Brun–Titchmarsh estimates do not by themselves deliver the distribution theorem needed by that route.

## Recovered analytic subseries

Five additional LaTeX sources were recovered during the September 11 estate sweep from an old directory named `zenodo-deposits`; nothing had actually been deposited there. Some were cited elsewhere in the paper estate, making their previous invisibility a real publication/discoverability defect.

They include two explicitly labelled skeletons, the 671-line Gamma-fiber local-density development, and two targeted attempts at named analytic gaps. Their states are preserved rather than being silently promoted to finished papers.

See [`docs/RECOVERED-ANALYTIC-ROUTE.md`](docs/RECOVERED-ANALYTIC-ROUTE.md) for the five-file index and the exact relationship to the other #203 repositories.

## Relationship to the other #203 repositories

- `jaredwilder/erdos203` is the finite prime-fibre obstruction program, with exact computations, replay code and finite covering impossibility results;
- `jaredwilder/erdos203-obstruction-calculus` collects the subgroup-obstruction calculus, the first five papers, supporting verification, and the dependency structure around the conditional final step;
- this repository is the **full paper-series home**, papers 1 through 17 plus the Gamma-fiber companion material and the recovered analytic subseries index.

This division is by mathematical role, not by which session or tool produced the artifact.

## Suggested submission order from the author's notes

1. Paper 1 — subgroup obstruction calculus — JNT or *Acta Arithmetica*.
2. Paper 5 — failed-route / obstruction analysis — *Bulletin of the AMS* or *Expositiones Mathematicae*.
3. Papers 6 and 2 — the rank-`r` pair — JNT or *Acta Arithmetica*.
4. Paper 17 — sharp dichotomy — *Mathematics of Computation*, JNT, *Acta Arithmetica*, or *Compositio*.
5. Gamma-fiber companion note — JNT note.

These are submission suggestions from the research notes, not publication or peer-review status.

## License

Apache-2.0.
