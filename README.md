# Parallel Computing in Python with Dask @ MadPy

This repository contains the materials for my "Parallel Computing in Python with Dask" talk at the Madison Python (MadPy) Meetup. 


## Installation

**Step 1: Create Conda environment**

A Conda environment with the dependencies needed to run the notebook from this talk can be created with:

```terminal
conda env create --file environment.yml
```

**Step 2: Activate Conda environment**

Activate the Conda environment:

```terminal
conda activate madpy-dask
```

**(Optional) Step 3: Install JupyterLab extension**

The [Dask JupyterLab extension](https://github.com/dask/dask-labextension) can be installed with:

```terminal
jupyter labextension install dask-labextension
```

inside the activated Conda environment.


## Usage

The notebook can be launched with:

```terminal
jupyter lab dask-demo.ipynb
```