# Missing Values Practice Repo

This folder contains simulated datasets, each illustrating a common missing-data mechanism or scenario. Pair each CSV with a Jupyter notebook that:
1) Diagnoses the missingness (MCAR/MAR/MNAR/other)  
2) Chooses and justifies an imputation/handling strategy  
3) Evaluates impact on downstream analysis/modeling  
4) Summarizes a recommended playbook for similar cases


## Suggested Notebook Outline
- Problem framing & business context
- Missingness audit: counts, % by column, patterns (heatmap/matrix), MCAR tests (Little’s test if applicable)
- Strategy options: drop vs simple vs group-wise vs model-based (KNN, MICE, regression, interpolation, ffill/bfill, domain rules)
- Quality checks: distribution shift, correlation preservation, leakage risks
- Documentation: decisions, pros/cons, when to revisit; add a `_missing_flag` when appropriate
