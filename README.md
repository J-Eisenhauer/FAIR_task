# Permutation entropy: white noise vs Brown noise

A small reproducible Jupyter workflow comparing normalized permutation entropy
(m = 4) for white noise and Brown noise.

## Design

- 1,000 samples per realization
- 100 independent realizations per process
- normalized permutation entropy with m = 4 and tau = 1
- deterministic random seed
- mean and sample standard deviation across realizations
- time-series and entropy visualizations

## Run

```bash
conda env create -f environment.yml
conda activate permutation-entropy-workflow
jupyter lab
```

Then open `permutation_entropy_white_vs_brown.ipynb` and run all cells.

## Files

- `permutation_entropy_white_vs_brown.ipynb` – full workflow
- `environment.yml` – pinned Conda environment

Before submission, test the repository once in a fresh environment created
only from `environment.yml`.
