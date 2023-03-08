# Havvarsel flux investigations
Numerical experiments for investigating and exposing artefacts in a well-balanced finite-volume method used for rotational shallow water flow in Havvarsel.

## Dependencies 
The numerical solvers for the rotational shallow-water equations are implemented in `metno/gpuocean` and only Jupyter notebooks with the experiments are provided here.
Follow the installation instructions in the `metno/gpuocean`-repository.

Last, set the `$PYTHONPATH` to find the source code from the `gpuocean` project within the environment. 
Therefore, run the following lines:
```
conda activate gpuocean
conda-develop /path/to/gpuocean/src
```
