# CosmoBen - Supernova Cosmology
In this project, we are performing a vanilla Bayesian inference of the cosmological parameters using the JLA data, which is publicly available [here](https://supernovae.in2p3.fr/sdss_snls_jla/ReadMe.html).

## Environment Setup
Assuming we have `anaconda3` setup, we can create a virtual environment using

```
conda create --name cosmoben python=3.9
```

To activate this environment, use

```
conda activate cosmoben
```

To deactivate an active environment, use

```
conda deactivate
```

Next, we can install the libraries found in the `requirements.txt` file as follows:

```
pip install -r requirements.txt
```
