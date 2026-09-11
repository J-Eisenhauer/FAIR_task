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


Relation to the FAIR principles

FAIR stands for Findable, Accessible, Interoperable, and Reusable.

Findable

The workflow is available in a public GitHub repository with a descriptive repository name, README, and repository metadata. A future archived release, for example through Zenodo, could additionally provide a persistent DOI.

Accessible

The complete workflow can be downloaded directly from the repository. No external or proprietary input data are required, since all data used in the analysis are generated within the notebook using a documented random seed.

Interoperable

The analysis is implemented in Python using widely used open-source packages and standard file formats. Results can also be exported to non-proprietary formats such as CSV.

Reusable

The notebook documents the analysis method, parameters, random seed, software requirements, and interpretation of the results. The provided environment file specifies the required computational dependencies, while the repository license defines how the code may be reused.

Limitation

GitHub provides transparency and version control, but it is not itself a permanent research archive. Long-term preservation could therefore be improved by archiving a release in a dedicated repository such as Zenodo.

## 

