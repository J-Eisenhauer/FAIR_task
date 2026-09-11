Permutation entropy: white noise vs. Brown noise



Small reproducible Jupyter workflow comparing normalized permutation entropy
of white noise and Brown noise.



The notebook generates synthetic data only; no external dataset is required.
In the current workflow, 100 realizations of each process are generated with
1,000 samples per realization and permutation entropy is calculated with
embedding dimension m = 4.



RUN 


conda env create -f environment.yml
conda activate permutation-entropy-workflow
jupyter lab


Then open permutation\_entropy\_FAIR\_task.ipynb and run all cells from top
to bottom.

## 

FILES



permutation\_entropy\_FAIR\_task.ipynb – complete analysis

environment.yml – pinned software environment

## 

