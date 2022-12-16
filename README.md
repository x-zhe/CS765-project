# CS765-project

This repository contains the dataset and codes suppporting our dimension reduction, clustering, and visualization of American Time Usage Survey (ATUS) data. The final visualization product can be found from the following site:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/x-zhe/CS765_project/HEAD?urlpath=voila%2Frender%2Fcodes.ipynb)

Some explanations of what is here:

* atus_embed_cluster.csv

The ATUS dataset. Downloaded from https://pages.graphics.cs.wisc.edu/765-22/datasets/atus/.

* umap_trying2_for_artifact.ipynb

A Jupyter notebook using Python to implement dimension reduction and clustering. It requires installing pandas, numpy, sklearn, matplotlib, seaborn, umap, hdbscan to run.

* codes.ipynb

A Jupyter notebook using Python to make interactive visualization. It requires installing plotly, matplotlib pandas, numpy, scipy, and ipywidgets to run.

* requirements.txt

A list of required packages to support deployment of the interactive visualization on MyBinder.org.
