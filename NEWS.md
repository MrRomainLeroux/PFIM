# PFIM 7.0.0

## Major changes
- Complete package redesign using functional programming.
- Breaking changes requiring updates from PFIM 6.1 scripts.
- New PK/PD modeling capabilities.
- Improved Bayesian FIM estimation.
- New multi-dose bolus ODE models.
- Updated vignettes with step-by-step workflow.

## Migration notes
- `modelEquations` structure updated.
- New `modelFromLibrary` mechanism.
- Error model uses `outputs` instead of `outcomes`.
- ODE initial conditions use `dose_C1` instead of `dose`.
- Administration constraints now use lists instead of vectors.
- Evaluation uses `outputs` and `fimType`.
- Sensitivity indices plotting function renamed.
