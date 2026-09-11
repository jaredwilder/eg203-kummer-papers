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

## Relationship to `erdos203-obstruction-calculus`

- `jaredwilder/erdos203-obstruction-calculus` collects the subgroup-obstruction calculus, the first five papers, supporting verification, and the dependency structure around the conditional final step;
- this repository contains the **full paper series**, papers 1 through 17 plus the Gamma-fiber companion note, including twelve sources not present in the smaller obstruction-calculus repository.

## Suggested submission order from the author's notes

1. Paper 1 — subgroup obstruction calculus — JNT or *Acta Arithmetica*.
2. Paper 5 — failed-route / obstruction analysis — *Bulletin of the AMS* or *Expositiones Mathematicae*.
3. Papers 6 and 2 — the rank-`r` pair — JNT or *Acta Arithmetica*.
4. Paper 17 — sharp dichotomy — *Mathematics of Computation*, JNT, *Acta Arithmetica*, or *Compositio*.
5. Gamma-fiber companion note — JNT note.

These are submission suggestions from the research notes, not publication or peer-review status.

## License

Apache-2.0.