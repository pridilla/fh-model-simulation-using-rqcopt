# Riemannian Quantum Circuit Optimization for Simulating the Fermi-Hubbard Model #

This is a reference code to the Bachelor's thesis Riemannian Quantum Circuit Optimization for Simulating the Fermi-Hubbard Model.

## Requirements ##

To run this notebook correctly, it is necessary to install the [original Python version of the rqcopt library](https://github.com/qc-tum/rqcopt) or its optimized C version. The latter one is not made public yet. For MacOS users, the dynamic library <code>rqcopt_lib.dylib</code> can be directly used. The python version can be installed globally with:

```
python3 -m pip install rqcopt
```

Other requirements can be installed to your local conda environment with:

```
conda install --yes --file requirements. txt
```
