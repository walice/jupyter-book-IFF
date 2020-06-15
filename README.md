# Unsupervised learning for illicit activity

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/walice/jupyter-book-IFF/gh-pages?urlpath=lab/tree/work/_sources/Unsupervised-learning-trade.ipynb)

## Jupyter Book
This project is written up as a Jupyter Book available at <https://alicelepissier.com/jupyter-book-IFF/>. See the GitHub repo :octocat: <https://github.com/walice/jupyter-book-docker> for instructions on how to create a Jupyter Book on a Docker container and host it with GitHub pages.


## Docker container on VM

Credit to [@syoh](https://github.com/syoh) for setting up the initial Docker image and for help setting up the computational environment. See the GitHub repo :octocat: <https://github.com/dddlab/reproducibility-demo/tree/prep-for-binder> for a demo on spinning up Docker containers that work with [Binder](https://mybinder.org).

* Start a Jupyter Notebook environment with `docker-compose.yml`
* The Docker image will be created from `Dockerfile` and includes the necessary packages to run Jupyter Book
* `setup.sh` will download a utility to create a password and encryption keys for your Jupyter notebook


## Goals of the project

This project works with the latest trade mis-invoicing estimates of the United Nations Economic Commission for Africa: Lépissier, Alice, Davis, William, & Ibrahim, Gamal. (2019). Trade Mis-Invoicing Dataset (Version 1). <a href="https://doi.org/10.5281/zenodo.3610558"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.3610558.svg" alt="DOI"></a>

While generating estimates of the dollar value of illicit trade has been helpful to shed light on the severity of the problem, the next step in the analysis is to further understand the nature of the illicit activity in terms of its origins, destinations, and sectors.

Therefore, the goal of this project is to extract meaningful insights on illicit trade using unsupervised machine learning techniques. By doing so, I can identify analytically relevant categories and dimensions of variation, in order to generate hypotheses and guide further work.

This project will apply the following techniques to the data:
1. Dimension reduction using Principal Components Analysis (PCA)
2. Clustering
3. Graph analysis