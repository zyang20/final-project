# Final Project Template

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/py4ds/final-project/master?urlpath=lab/tree/final-project.ipynb)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/py4ds/final-project/blob/master/final-project.ipynb)

This repository contains a template for final projects.

## How to Use this Template

### Work in Binder
- Launch a live notebook server with the notebook using [Binder](https://beta.mybinder.org/): [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/py4ds/final-project/master?urlpath=lab/tree/final-project.ipynb)

### Work in Colab
- Launch an executable version of the notebook using [Google Colab](http://colab.research.google.com): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/py4ds/final-project/blob/master/final-project.ipynb)

### Work locally (requires local installation of [git](https://git-scm.com/) and [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html))
- Clone the repo using a shell (below) or [GitHub Desktop](https://desktop.github.com)

```sh
git clone https://github.com/py4ds/final-project
cd final-project
jupyter lab
```

# Required packages

The packages used to run the code in the Binder instances are listed in [requirements.txt](requirements.txt) (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use).

To install the requirements using [pip](http://conda.pydata.org), run the following at the command-line:

```sh
$ pip install --requirement requirements.txt
```

To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:

```sh
$ conda install --file requirements.txt
```

To create a stand-alone environment named ``final-project`` with Python 3.6 and all the required package versions, run the following:

```sh
$ conda create -n final-project python=3.6 --file requirements.txt
```

You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation.


## License

The code in this repository is released under the [MIT license](LICENSE-CODE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT).

