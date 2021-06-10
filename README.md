# Item-Response-NBA

This notebook contains an analysis of latent skills of NBA players when involved in a play where a foul was or might have been called. The analysis is performed with a Bayesian Item Response Rasch model with hierarchical structure. The software used is [PyMC3](https://docs.pymc.io/). This notebook is based on Austin Rochford blog post [NBA Foul Calls and Bayesian Item Response Theory](https://www.austinrochford.com/posts/2017-04-04-nba-irt.html).



### How to easily use this notebook
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
