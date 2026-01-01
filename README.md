This repository contains simulation code and replication files for a synthetic business research paper studying how AI adoption affects firm decision hierarchies.

The notebook business_rp_simulations.ipynb generates all data and tables used in the paper.

Outputs:
- data/panel_data_example.csv: example firm-level panel
- tables/table_simulation_results.csv: Monte Carlo simulation results
- metadata/dgp_parameters.csv: true parameters used in the data-generating process

All results are reproducible by running the notebook top-to-bottom.

## Scope and Interpretation

This repository accompanies a simulation-based study examining
identification and measurement issues in estimating AI-induced changes
in organizational hierarchies.

All data are synthetic and generated from a transparent DGP.
The goal is not to estimate real-world effects, but to evaluate
econometric performance under plausible AI adoption processes.
