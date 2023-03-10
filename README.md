# Havvarsel flux investigations
Numerical experiments for investigating and exposing artefacts in a well-balanced finite-volume method used for rotational shallow water flow in Havvarsel.


## Dependencies 
The numerical solvers for the rotational shallow-water equations are implemented in the [`gpuocean`-project](https://github.com/metno/gpuocean) and only Jupyter notebooks with the experiments are provided here.

Follow the installation instructions in the [`gpuocean`-repository](https://github.com/metno/gpuocean).
Remeber to set the `$PYTHONPATH` so that the notebooks in this repo manage to import the `gpuocean` code:
```
conda activate gpuocean
conda-develop /path/to/gpuocean/src
```

## Reproducing Results
The plots in the proceedings article *Reducing Numerical Artifacts by Sacrificing Well-Balance for Rotating Shallow Water Flow* by Håvard Heitlo Holm and Florian Beiser (submitted for review) are generated in the following notebooks in this repository:
- Figure 1: `Bump.ipynb`
- Figure 2: `RossbyAdjustment.ipynb`
- Figure 3: `KelvinWave.ipynb`
- Figure 4: `DoubleJet.ipynb`
- Figure 5: `Lovese.ipynb`
