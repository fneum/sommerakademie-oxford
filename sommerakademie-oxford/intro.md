# Overview

This website introduces you to the basics of using PyPSA for energy system modelling.

PyPSA is an open-source Python framework and stands for **Python for Power
System Analysis**.

PyPSA is made for optimising and simulating modern power and energy systems that
include features such as conventional generators with operational constraints,
variable wind and solar generation, hydro-electricity, storage, coupling to
other energy sectors, and linearised power flow with loss approximations.

:::{note}
Checkout the [documentation](https://pypsa--1250.org.readthedocs.build/en/1250/)
for more details.
:::

For working with PyPSA, we will need to cover some Python and `pandas` basics.
Python is a programming language that is widely used in scientific computing and
data analysis. `pandas` is the core library for handling tabular data in Python.
Think of it as Excel but with code.

## Installation

Below you can find three installation options. You only need one!

### Google Colab

You can run the examples without a local Python installation using [Google Colab
(colab.google)](https://colab.google) which provides an online Python
environment. This requires a Google account.  Click on the rocket in the top
right corner and launch "Colab". If that doesn't work download the `.ipynb` file
and import it in [Google Colab](https://colab.research.google.com/).

:::{note}
This is the easiest option for Python beginners!
:::

### conda

Install `conda` by following [these instructions](https://docs.conda.io/projects/conda/en/stable/user-guide/install/index.html).

The `conda` environment specification can be downloaded here:

    https://github.com/fneum/sommerakademie-oxford/blob/main/environment.yaml

Navigate to the directory containing the `environment.yaml` file and run:

    conda env create -f environment.yaml

Activate the environment with:

    conda activate oxford


### uv / pip

Install `uv` by following [these instructions](https://docs.astral.sh/uv/getting-started/installation/).

The environment specification can be downloaded here:

    https://github.com/fneum/sommerakademie-oxford/blob/main/requirements.txt

Navigate to the directory containing the `requirements.txt` file and run:

    uv venv
    source .venv/bin/activate
    uv pip install -r requirements.txt


## Usage

If you chose Google Colab, you can run the notebook cells directly without any additional setup.

If you chose a local installation, you can run the notebooks in the terminal with:

    # first navigate to the notebook directory with cd (stands for change directory)
    cd path/to/your/notebook

    # then start jupyter lab
    jupyter lab

This will open the Jupyter Lab interface in your web browser, where you can interact with the notebooks.
If the browser does not open automatically, you can manually navigate to `http://localhost:8888`.
