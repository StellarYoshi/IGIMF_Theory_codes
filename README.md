# IGIMF_Theory_codes
This repository contains codes to generate data samples of stars for star clusters or even whole galaxies. It is based on the IGIMF Theory and similar to the galIMF code by Yan Zhiquiang et al. In contrast to their codes, this module calculates the discrete stellar masses. This allows more easily to simulate composite IMFs of star-forming regions.

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
