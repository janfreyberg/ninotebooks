# Receptive field mapping with SamSRF

In this folder you'll find a few notebooks that walk you through receptive field mapping with [SamSRF](https://figshare.com/articles/SamSrf_toolbox_for_pRF_mapping/1344765).

The notebooks will run you through:
1. Fitting a receptive field model to your data
2. Delineating the visual cortex

### Requirements

You will need:

- [Jupyter notebook](http://jupyter.org/) (install it alongside python 3.5 by installing [Anaconda](https://www.continuum.io/downloads) or by running `pip install jupyter` if you already have python installed)
- `[Matlab 2016a or higher](https://www.mathworks.com/products/matlab.html)` and the `[matlab_kernel](https://github.com/Calysto/matlab_kernel)`. Note that you need the Statistics & Optimization Toolboxes alongside your Matlab installation.
- `[SamSrf](https://figshare.com/articles/SamSrf_toolbox_for_pRF_mapping/1344765)` (make sure it's on your Matlab path - inside the Matlab GUI, click Set path).
- SPM8 or above
- `[FreeSurfer](https://surfer.nmr.mgh.harvard.edu/)` 5.0 or later (this means this notebook only runs on Lunix or Mac)
- The sample data from the cookbook

### Getting Started

As for all of the neuroimaging notebooks, you can download the `.ipynb` files individually, or clone the whole repository onto your computer.

Then open a terminal and navigate to the folder where the notebooks are saved; then open the jupyter notebook app by typing `jupyter notebook`. This should open a browser window with an overview of your folder.

If you are familiar with the concept behind receptive field mapping, you can then get started with the first notebook (`01-model-fitting.ipynb`). If not, the SamSRF toolbox comes with a great introduction by Sam Schwarzkopf, which I've included [here]().