

** Dask tutorials developed by Alex K. ** 



# Install all dask components
dask_side[https://docs.dask.org/en/latest/install.html]


The following command installs dask and all dependencies (including, `NumPy`, `Pandas`, `Toolz`, `Tornado`) required by following dask modules:  `dask.array`, `dask.dataframe`, `dask.delayed`, `dask.distributed`


```bash
pipenv install "dask[complete]"

```

- The core dask library can be installed by omitting the bracketed argument.
- Dask modules & corresponding requirements can be installed individually; substitute module name in place of complete.

