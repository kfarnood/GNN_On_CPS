# GNN_On_CPS
Label-Efficient GNN for Molecular Triage. Solves the HPC bottleneck. Uses 8 percent labels with Cross Pseudo Supervision to train in 1.6 hours. Achieves 2x faster convergence than the stability baseline. This system is a resource-constrained pre-filter for drug discovery.


RESOURCE CONSTRAINED MOLECULAR TRIAGE

This system provides a high-efficiency solution for molecular property prediction under strict hardware and label constraints.

Our approach uses a custom GNN with Cross Pseudo Supervision (CPS) to create a Stage 1 Triage Filter.

FINAL RESULTS:

Efficiency: Achieved optimum results in 1.6 hours, proving to be 2 times faster than the stability baseline.

Quality: Maintained strong ranking fidelity (Pearson R near 0.78), enabling accurate filtering of candidates.

Use Case: The model is an ideal, resource-constrained front-end for accelerating drug discovery pipelines that rely on expensive SOTA simulations.


AI help : DeepSeek with debugging , plot codes, report codes. Gemini with logic check, Claude value check, Grok with comparing to other papers. GPT was useless (as always) . Perplexicity with
comparison with other papers and methods.
