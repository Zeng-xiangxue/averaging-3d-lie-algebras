# Verification package: averaging operators on three-dimensional real Lie algebras

This package accompanies the paper "Complete classification of averaging operators on
three-dimensional real Lie algebras" (X. Zeng, K. Zheng).

All computations were carried out with Wolfram Mathematica (version 13 or later).
Each script is self-contained: evaluate the whole notebook and it prints the
verification message together with the residual, the Groebner basis or the
unit-ideal flag.

## How to reproduce
1. Open a script from scripts/ in Mathematica and evaluate it (Shift+Enter).
2. Compare the printed output with the corresponding file in outputs/.

## What each group of scripts checks
- _dim3_*.wl : classification of three-dimensional real Lie algebras (Theorem 2.2).
- _check_a3*.wl, _a3_so3_check*.wl : solution sets on the abelian algebra a3 and on so(3).
- _h1_*.wl : the nine classes on the Heisenberg algebra h1 and their pairwise non-conjugacy.
- _r3_setup*.wl, _r3_check*.wl, _r3_verify4.wl, _aut_r3*.wl : automorphisms of r3, the six classes, residual tests.
- _r3lam_setup.wl, _r3lam_check.wl, _r3lam_m1_check.wl, _r3lam_gamma_kill*.wl : the eleven classes on r3,lambda, the branch a=0, the extra merges for lambda=-1.
- _r10_sys.wl, _r10_verify.wl, _r10_norm.wl : the sixteen classes on r(1,0) and the 120 pairwise unit-ideal tests.
- _rJ_branch.wl : the seven classes on r(J) and the 21 pairwise tests.
- _rC_check.wl, _rC_correct.wl, _rC_protocol.wl, _rcheck_mirror.wl, _e2_full.wl : the five classes on r(c), the sign of lambda, the mirror component for c=0 (10 pairs).
- _sl2_setup.wl, _sl2_selfadj*.wl, _sl2_rank*.wl, _sl2_kernel_check.wl, _sl2_szero*.wl : K-self-adjointness, exclusion of rank 2, the six classes on sl(2,R).
- _so3_avg_*.wl, _check_so3*.wl, _check_sl2_so3.wl : the three classes on so(3), compact/split comparison.
- _rbo_criterion.wl, _rbo_ext.wl, _rbo_r3_r3lam.wl : the criterion [g, im T] contained in ker T and the comparison with zero-weight Rota-Baxter operators.
- _m5_gb.wl, _check_ext_review*.wl, _rev_M1.wl, _rev_M3M1M2M6.wl, _rev_M6.wl : unit-ideal (Groebner) computations for pairwise non-conjugacy and revision checks.
- _ref_check.wl : consistency of the residual identities quoted in the text.
