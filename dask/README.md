

** Dask tutorials developed by Alex K. ** 



### Dask
- parallel processing library for scalable, distributed computing in Python
- memory-efficient parallel arrays, dataframes & lists that extend functionality of Numpy, Pandas, & Python iterators, while maintaining familiar interface
- computation optimized dynamic task schedulers (similar to Celery, Make, Airflow) that operate over collections

[Dask website](https://docs.dask.org/en/latest/install.html)


The following command installs dask and all dependencies (including, `NumPy`, `Pandas`, `Toolz`, `Tornado`) required by following dask modules:  `dask.array`, `dask.dataframe`, `dask.delayed`, `dask.distributed`


```bash
pipenv install "dask[complete]"

```

- The core dask library can be installed by omitting the bracketed argument.
- Dask modules & corresponding requirements can be installed individually; substitute module name in place of complete.

