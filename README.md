# FoldMal
## Abstract
This is the notebook for the analysis of differential expression data from birds infected with Avian Malaria. The purpose is to identify how the significant genes lie on the distribution of fold change across two time points. 

## Instructions
In order to run this notebook, download this repo from github (export it or clone it), you can install all the dependencies manually, or set up an environment using [conda](https://docs.anaconda.com/anaconda/install/)

Extract the tarball if you downloaded, but otherwise change directory to the new folder.

The dependencies are:
1. python3
2. matplotlib - plotting
3. pandas - read and manipulate tabulated data
4. numpy - numerical operations on tabulated data
5. jupyter - Runs the notebook

Once you have conda installed, you can set up the environment with all of those dependencies:

`conda env create -f foldmal_env.yml`

`conda activate foldmal_env`

To run the notebook, type

`jupyter-notebook`

A browser window will open, and display the active directory, which should include the FoldMal.ipynb file. Click on it, and enjoy!
