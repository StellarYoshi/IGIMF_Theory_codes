# IGIMF_Theory_codes
This repository contains codes to generate data samples of stars for star clusters or even whole galaxies. It is based on the IGIMF Theory and similar to the [galIMF](https://github.com/Azeret/galIMF) code by Yan Zhiqiang et al. In contrast to their codes, the main focus of the provided code are sub-galactic regions, especially composite IMFs, instead of galaxy-wide stellar populations. Further, the code in this module calculates the discrete stellar masses instead of histograms. This allows for more exact simulations of dynamical processes within star-forming regions, such as dynamical ejections.

## Contents

* IMF_sampling: Generates optimally sampled stellar Initial Mass Functions (IMFs)
* ECMF_sampling: Generates optimally sampled Embedded Cluster Mass Functions (ECMFs) within the IGIMF Theory as well as custom star cluster samples
* cIMF_and_IGIMF_sampling: Generates optimally sampled Integrated Galactic IMFs (IGIMFs) and custom composite IMFs (cIMFs)
* cIMF_generating_optimal: Calculates the optimally sampled cIMF of a custom star cluster sample. Allows to investigate the cIMF form without drawing stellar masses
* cIMF_generating_random: Similar to cIMF_generating_optimal but for randomly sampled stellar IMFs. Allows for comparison between optimally and randomly sampled cIMFs

## Installation

To run the demo notebook, first install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running the Demo

After installing the dependencies, you can run the Jupyter notebook:

```bash
jupyter notebook OSGIMF_Master_Function.ipynb
```

Alternatively, you can use JupyterLab:

```bash
pip install jupyterlab
jupyter lab OSGIMF_Master_Function.ipynb
```

## Dependencies

- **numpy**: Numerical computing library
- **scipy**: Scientific computing library (for optimization and integration)
- **matplotlib**: Plotting library
- **jupyter**: Interactive notebook environment
