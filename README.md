# ecap-fau-z0experiment
Scripts and notebook for the Z0 experiment of the F-Pratikum of ECAP/FAU, Erlangen.

Authors:
Rodrigo Guedes Lang (rodrigo.lang@fau.de)
Pedro Ivo Silva Batista (pedro.batista@fau.de)

# Prerequisites

1. A [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installation.

2. In order to ensure a proper installation of all the dependecies required, we recommend a conda installation, like [anaconda](https://docs.anaconda.com/free/anaconda/install/) or [mamba](https://mamba.readthedocs.io/en/latest/installation/mamba-installation.html).

The following instructions assume that you already have installed the prerequisites.

# Cloning the repo

Go into your preferred folder, and clone the repository with:

`git clone git@github.com:rodrigoglang/ecap-fau-z0experiment.git`

# Create a conda environment

Now we want to install all the dependencies required to run the notebooks in this repo.
For that, you will use either `conda` or `mamba`:

```
cd ecap-fau-z0experiment
conda env create -f environment.yml
conda activate z0-fp
```