[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fair-software/howfairis-notebooks/main?filepath=demo.ipynb)

Jupyter notebook demo of [howfairis](https://github.com/matchms/matchms) functionality.

Prerequisites

For running locally on Ubuntu:

```shell
sudo apt install jupyter-core
sudo apt install jupyter-notebook
```

Install Miniconda or Anaconda from https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html

Create a conda environment:

```shell
conda env create
```
Activate the conda environment:

```shell
conda activate howfairis-notebooks
```

Check to see if it all worked by listing the packages that are present in the
conda environment named ``howfairis-notebooks``:

```shell
conda list
```

This should yield a table of packages alongside where they were installed from. If everything looks OK, start the
notebook server:

```shell
jupyter notebook
```

And open a browser to http://localhost:8888 to interact with the notebook.
