# SPIBACK

The SPIral arms & Bar bACKward integrations (SPIBACK) Jupyter Notebook generates Milky Way models through the backward integration method, and allows users to plot the 2D local velocity space distribution at the Sun's position, as well as median Galactocentric radial velocity maps across the area of the Galactic disk probed with Gaia DR3. This can be done for different bar and spiral arms parameters. The parameters are set by default to be those of the "fiducial model", see Khalil et al for all the details: https://...

## Installation

This Notebook crucially needs the installation of:

- PyTorch: https://pytorch.org

- AGAMA: https://github.com/GalacticDynamics-Oxford/Agama 

The latter can be simply installed with: pip install agama

Then, install: pip install torchdiffeq 

Scipy and Matplotlib are also needed

# Basic usage

Simply download the files and run them in a single folder on a Jupyter lab or Jupyter notebook interface. Run all the cells of the spiback_minimalversion_run.ipynb Notebook to display the plots properly. This is a Python3 notebook, which needs Python 3.10 or above.

You can set the model parameters as you wish in spiback_minimalversion_run.ipynb 

One important parameter is bins_model. This is set by default to 32+1 taking about 2 hours to complete. A value of 16+1 can be used for quick tests. A value of 64+1 will give a much better resolution, equivalent to that used to plot the data, but will significantly increase the computation time.

Currently only a minimal version of the code is available for quick computations. A fuller version will be provided soon. 

## Contributing

Suggestions are welcome. 

# Attribution

If you make use of this notebook in your research, please acknowledge Khalil et al. 


