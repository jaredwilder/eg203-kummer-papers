# papers/

17 numbered papers + Companion note. Single source of truth for the EG203 corpus.

## Files

| File | Apex round | What it is |
|------|-----------|-----------|
| `01_subgroup_obstruction_calculus.tex` | — | Elementary submission candidate. Subgroup obstruction calculus for two-generator exponential congruences. |
| `02_crt_synchronization_projective_slopes.tex` | R753-extended | Algebra paper. CRT synchronization + projective Kummer slopes + rank-$r$ section. |
| `03_density_zero_kummer_obstruction_schema.tex` | — | Density-zero schema. Conditional on Pappalardi + sieve normalization. |
| `04_kummer_distribution_criterion.tex` | — | Conditional architecture paper. PHNC/KRWS/KRC/RTHLS/Kummer-BV/BVK hypothesis-status table. |
| `05_failed_routes_phnc_audit.{tex,pdf}` | — | Defensive publication. Why BFI / Plünnecke–Ruzsa / fixed-field Chebotarev / order bounds / generic Chebotarev-BT don't close the high-seam PHNC route. |
| `06_rank_r_synchronization_projective_kummer_geometry.{tex,pdf}` | R753 | Rank-$r$ synchronization + projective Kummer geometry + prime-power Hensel lifting. Companion to Paper 2. |
| `07_exact_distribution_matroid_lifting_addenda.{tex,pdf}` | V11/V12 apex | Exact distribution + matroid lifting addenda. |
| `08_kummer_fourier_collision_variance.{tex,pdf}` | — | Iteration paper. Kummer Fourier collision variance. |
| `09_kummer_cut_gap_bounds.{tex,pdf}` | — | Iteration paper. Kummer cut-gap bounds. |
| `10_kummer_row_balance_chebotarev_matroid_link.{tex,pdf}` | — | Iteration paper. Row balance + Chebotarev matroid link. |
| `11_phnc_to_angular_collision_bridge.{tex,pdf}` | — | Iteration paper. PHNC ↔ angular collision bridge. |
| `12_kummer_fourier_smoothing_and_krws.{tex,pdf}` | V13 apex | Kummer Fourier smoothing + KRWS, with Bernoulli-extremal appendix. |
| `13_diagonal_barrier_kummer_large_sieve.{tex,pdf}` | — | Iteration paper. Diagonal barrier + Kummer large sieve. |
| `14_bad_character_sparsity_phnc_barrier.{tex,pdf}` | — | Iteration paper. Bad-character sparsity + PHNC barrier. |
| `15_discriminant_barrier_and_bilinear_kummer_equivalence.{tex,pdf}` | V13 apex | Discriminant barrier theorem + PHNC ⇔ TKB$_\ell$ bilinear equivalence. |
| `16_localizing_the_high_l_kummer_obstruction.{tex,pdf}` | V14+V15 apex | Localizing the high-$\ell$ Kummer obstruction. 5 thms (Conductor Identity, Descent Emptiness, Iwasawa Decoupling, Family-Averaging Dilution, Spiegelungssatz Bridge) + Siegel-free ZFR + 7-wall synthesis. |
| **`17_sharp_dichotomy_phnc_seam.tex`** | **V16+V17 apex** | **Sharp Dichotomy at $\ell\log\ell \asymp \log Q$.** Unconditional unlock + JANG no-go + CTREX no-Siegel-zero + Artin-NG + Cross-Field Conductor Explosion. The headline result of the program. |
| `companion_gamma_fiber_local_density.tex` | R682+R753 | Companion note. Exact Γ-fiber local density + R753 prime-power Hensel addendum. |

## Submission priority

1. Paper 1 → JNT or Acta Arith
2. Paper 5 → Bulletin AMS or Expositiones
3. Papers 6+2 (rank-$r$ pair, R753) → JNT or Acta Arith
4. Paper 17 (Sharp Dichotomy) → Math. Comp., JNT, Acta Arith, or Compositio
5. Companion Γ-fiber note → JNT note or supporting document

## Naming convention

- `NN_descriptive_name.tex` — main source
- `NN_descriptive_name.pdf` — compile-clean PDF where available
- Lowercase, underscores, no spaces.
- Paper 17 is the most recent (V16+V17 Sharp Dichotomy, drafted 2026-05-13).

## Verification

Run `../swarm/verify_all_papers.sh` after any edits to ensure all papers still compile clean.

## Compile requirements

- LaTeX (pdflatex) with standard amsmath/amssymb/amsthm/mathtools/enumitem/hyperref/cleveref packages.
- Local compile attempted via Docker TeX Live 2026 image (Paper 6 confirmed compile-clean; Paper 17 needs local check by operator).
