# 👋 Hi, I'm Lionel

*PhD student in Bioengineering, University of Washington · [Imoukhuede Lab](https://sites.bioe.uw.edu/imoukhuede/) · expected 2027*

I build computational models of oxytocin receptor (OXTR) signaling, from literature-scale parameter
synthesis through mechanistic simulation to generative ligand design.

## What I work on

- **Calibrated uncertainty for small-data property prediction.** GNN ensembles with temperature
  scaling, isotonic CDF recalibration, scaffold-based splits, CRPS and interval coverage.
  Code: [oxtr-gnn-calibration](https://github.com/Ara101/oxtr-gnn-calibration)
- **Kinetic meta-analysis of Class A GPCR signaling.** Bayesian hierarchical (PyMC) and REML
  random-effects (metafor) pooling of rate constants across 57 studies, with heterogeneity
  quantification and simulation-based power analysis. Curated dataset and analysis code release with
  the manuscript.
- **Mechanistic ODE modeling of receptor signaling.** Mass-action models of OXTR-Gq membrane dynamics
  in Tellurium and SimBiology, global sensitivity analysis, identifiability triage, and model
  selection by AIC/BIC and likelihood ratio tests.
- **Biased agonist design.** DrugEx graph transformer fine-tuning, multi-objective reinforcement
  learning, QSPR reward models, and dual-state docking, run as a checkpointed Snakemake workflow
  under SLURM.
- **Reproducible scientific computing.** Making all of the above run end to end on someone else's
  machine. Worked example:
  [recapitulating a published GPCR model](https://github.com/Ara101/Recapitulating-Shankaran2007-GPCR-model)

## 🌱 Currently

Extending the generative work toward pathway-selective ligand design, and moving three computational
OXTR projects toward publication.

## Looking to collaborate on

Systems-level modeling of biological systems, especially GPCR pharmacology and signal transduction.
Also happy to talk with anyone building parameter databases or doing meta-analysis in pharmacology.
That tooling is badly underbuilt.

## 🛠️ Tools

- **Modeling & inference** `Python` `NumPy/SciPy` `PyMC` `pandas` `R (metafor)` `Tellurium` `MATLAB SimBiology`
- **ML** `PyTorch` `scikit-learn` `GNNs` `DrugEx` `QSPR` `SALib`
- **Cheminformatics & structure** `RDKit` `GNINA`
- **Infrastructure** `Docker/Apptainer` `SLURM (UW Hyak)` `Snakemake` `Git` `WSL` `Conda`

## 📫 Reach me

[LinkedIn](https://linkedin.com/in/kltukei) ·
[Email](mailto:Lionel.tukei@gmail.com) ·
[Google Scholar](https://scholar.google.com/citations?user=0XDjfKkAAAAJ&hl=en)
