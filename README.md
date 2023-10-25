# EDS Processing Notebooks

Jupyter notebooks for processing of multidimensional energy-dispersive x-ray spectroscopy (EDS) spectrum images using [HyperSpy](https://hyperspy.org/index.html).

The notebooks are work in progress. Please double check the analysis results!

### Installation steps for the Python environment

Install miniconda (or mamba). Then, I ran the following commands:

```console
conda create -n hspy175 python=3.10
```

```console
conda install hyperspy jupyterlab ipympl scienceplots watermark -c conda-forge
```

I got an error when loading the .bcf file with h5py. This got fixed by reinstalling h5py:

```console
conda install h5py --force-reinstall
```
