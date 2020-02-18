# Missing Data Imputation using Optimal Transport

## Overview

This repository complements ICML submission n°4195:

- `experiment.py` allows to reproduce the imputation benchmark therein;
- `imputers.py` contains the classes corresponding to algorithms 1 and 3;
- `data_loaders.py` contains data loading utilities for the UCI ML repository datasets on which experiments are run;
- `utils.py` contains methods of general utility, and the implementation of MAR and MNAR missing data mechanisms in particular;
- `softimpute.py` contains the implementation of the softimpute baseline.

## Dependencies
- [PyTorch](https://pytorch.org/)
- [GeomLoss](https://www.kernel-operations.io/geomloss/)
- [POT](https://pot.readthedocs.io/en/stable/)

To use the data loading utilities in `data_loaders.py`, [wget](https://pypi.org/project/wget/) is also required.
