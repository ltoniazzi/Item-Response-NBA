# Item-Response-NBA

This notebook contains an analysis of latent skills of NBA players when involved in a play where a foul was or might have been called. The analysis is performed with a Bayesian Item Response Rasch model with hierarchical structure. The software used is [PyMC3](https://docs.pymc.io/). This notebook is based on Austin Rochford blog post [NBA Foul Calls and Bayesian Item Response Theory](https://www.austinrochford.com/posts/2017-04-04-nba-irt.html). This notebook is also available within the official PyMC3 examples [here](https://github.com/pymc-devs/pymc-examples/blob/main/examples/case_studies/item_response_nba.ipynb).



## How to easily use this notebook

The easiest way is to simply click on this binder link

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ltoniazzi/Item-Response-NBA/3c6b15843a858ae65bdcc394191c19727fce38b8)

Alternatively, you can set up the repo locally using Anaconda following the simple four steps.

### 1. Clone the repository locally

In your terminal, use `git` to clone the repository locally.

```bash
git clone https://github.com/ltoniazzi/Item-Response-NBA.git
```

### 2. Download Anaconda

Download the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3.

### 3. Set up your environment

If this is the first time you're setting up your compute environment,
use the `conda` package manager
to **install all the necessary packages**
from the provided `environment.yml` file.

```bash
conda env create -f environment.yml
```

To **activate the environment**, use the `conda activate` command.

```bash
conda activate Item-Response-NBA
```

**If you get an error activating the environment**, use the older `source activate` command.

```bash
source activate Item-Response-NBA
```

To **update the environment** based on the `environment.yml` specification file, use the `conda update` command.

```bash
conda env update -f environment.yml
```




### 4 Open your Jupyter notebook in Jupyter Lab

In the terminal, execute `jupyter lab`.
