# Kinetic Modeling of Covalent Inhibition with Rapid Intermediates

The Jupyter notebook in this repository can be used to reproduce the kinetic modeling and analysis as discussed in [ref. 1][1].

## Environment

This notebook should work with Python 3.10, 3.11, and 3.12. The packages used are listed in `environment.yml` and `requirements.txt`.

### Dependencies

- `gekim` ([GeKiM](https://github.com/kghaby/GeKiM))
- `numpy`
- `lmfit`
- `matplotlib`

### Installation

Use the following command in the root of a local clone of this repository to create an environment `gekim` (or a name of your choice assigned in `environment.yml`) for the notebook:

```shell
conda env create -f environment.yml
```

Then,

```shell
conda deactivate
conda activate gekim
```

## References

1. Ghaby and Roux, 2025.

[1]: https://github.com/kghaby/GeKiM
