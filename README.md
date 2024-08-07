# Tutorial on basic reinforcement learning concepts

[![DOI](https://zenodo.org/badge/759758400.svg)](https://doi.org/10.5281/zenodo.12649046)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

- [Download the repository](#download-the-repository)
- [Getting started](#getting-started)
- [Running the tutorial](#running-the-tutorial)

## Material for this tutorial

- The theoretical lecture can be found here:
  - [Part 1: Introduction to reinforcement learning](https://github.com/machine-learning-tutorial/reinforcement-learning/blob/main/lectures/intro_to_RL.pdf)

- The tutorial can be found here:
  - [RL_simple_gridworld.ipynb](https://github.com/machine-learning-tutorial/reinforcement-learning/blob/main/RL_simple_gridworld.ipynb)
 
## Citing the tutorial

- This tutorial is registered in [Zenodo](https://zenodo.org/records/12649046).
- Please use this DOI when citing this material: [https://doi.org/10.5281/zenodo.12649046](https://doi.org/10.5281/zenodo.12649046)

```bibtex
@software{santamaria_garcia_2024_12649046,
  author       = {Santamaria Garcia, Andrea},
  title        = {Tutorial on basic reinforcement learning concepts},
  month        = jul,
  year         = 2024,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.12649046},
  url          = {https://doi.org/10.5281/zenodo.12649046}
}
```

## Download the repository

### Get the repository with Git

You will need to have Git previously installed in your computer.
To check if you have it installed, open your terminal and type:

``` bash
git --version
```

#### Git installation in MacOS

``` bash
brew update
brew install git
```

#### Git installation in Linux

In Ubuntu/Debian

``` bash
sudo apt install git
```

In CentOS

``` bash
sudo yum install git
```

Once you have Git installed open your terminal, go to your desired directory, and type:

``` bash
git clone https://github.com/machine-learning-tutorial/reinforcement-learning
cd reinforcement-learning
```

## Getting started

You need to install the dependencies before running the notebooks.

### Using conda

If you don't have conda installed already and want to use conda for environment management, you can install the miniconda as [described here](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html).

- Create a conda env with `conda create -n rl-tutorial python=3.10`
- Activate the environment with `conda activate rl-tutorial`
- Install the required packages via `pip install -r requirements.txt`.
- Run the following commands:

```bash
python -m jupyter contrib nbextension install --user
python -m jupyter nbextension enable varInspector/main
```

- **After the tutorial** you can remove your environment with `conda remove -n nn-tutorial --all`


## Running the tutorial

After installing the package

You can start the jupyter notebook in the terminal, and it will start a browser automatically

```bash
python -m jupyter notebook
```

Alternatively, you can use supported Editor to run the jupyter notebooks, e.g. with VS Code.

### Jupyter Notebooks

Use `cmd+Enter` to execute one cell block

### Part 1 Simple Gridworld (no ML libraries)

The first part of the tutorial is in `RL_simple_gridworld.ipynb`.


