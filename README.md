# EDS Processing Notebooks

Jupyter notebooks for processing of multidimensional energy-dispersive x-ray spectroscopy (EDS) spectrum images using [HyperSpy](https://hyperspy.org/index.html).

The notebooks are work in progress. Please double check the analysis results!

### Installation steps for the Python environment

Install miniconda (or mamba). Then, I ran the following commands:

```console
conda create -n hspy175 python=3.10
```

Main packages:

```console
conda install hyperspy jupyterlab ipympl watermark -c conda-forge
```

I got an error when loading the .bcf file with h5py. This got fixed by reinstalling h5py:

```console
conda install h5py --force-reinstall
```

Visualization/Plotting:

```console
conda install scienceplots glasbey seaborn -c conda-forge
```

## Notes

- A lot of useful information is provided in the [HyperSpy documentation](https://hyperspy.org/hyperspy-doc/current/index.html)
- Scikit-learn info on [MSA](https://scikit-learn.org/stable/modules/decomposition.html#decompositions)
