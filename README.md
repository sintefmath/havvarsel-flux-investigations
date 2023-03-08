# Havvarsel flux investigations
Numerical experiments for investigating and exposing artefacts in a well-balanced finite-volume method used for rotational shallow water flow in Havvarsel.

## Dependencies 
The numerical solvers for the rotational shallow-water equations are implemented in the [`gpuocean`-project](https://github.com/metno/gpuocean) and only Jupyter notebooks with the experiments are provided here.

Follow the installation instructions in the [`gpuocean`-repository](https://github.com/metno/gpuocean).
Last, set the `$PYTHONPATH` to find the source code from the `gpuocean`-project within the environment. 
Therefore, run the following lines:
```
conda activate gpuocean
conda-develop /path/to/gpuocean/src
```

## Reproducing Results
The plots in the proceedings article "XXX" of the Finite Volumes for Complex Applications 10 (FVCA10) symposium are generated in the notebooks in this repository:
- Figure 1: `Bump.ipynb`
- Figure 2: `RossbyAdjustment.ipynb`
- Figure 3: `KelvinWave.ipynb`
- Figure 4: `DoubleJet.ipynb`
- Figure 5: `Lovese.ipynb`
