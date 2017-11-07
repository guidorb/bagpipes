# BAGPIPES

### Bayesian Analysis of Galaxies for Physical Inference and Parameter EStimation

Bagpipes is a state of the art model galaxy generation framework and fitting tool. It is designed to generate a highly diverse range of complex model galaxy spectra, and to fit these models to arbitrary combinations of spectroscopic and photometric data using the MultiNest algorithm.

![](examples/example_pipes_model.pdf)

### Installation

Bagpipes setup is a fairly quick process. Simply clone this repository, add the bagpipes folder to your PYTHONPATH variable and install the Python package dependencies (astropy, corner) and you're ready to run the first example file. For fitting to be supported you must also install [MultiNest](https://github.com/JohannesBuchner/MultiNest) and the Python interface PyMultiNest which can be installed with pip.

You will also need to download at least one suite of BAGPIPES spectral models. These are relatively large and so are stored separately. Currently the only set of models pre-prepared are the BC03 miles models used in the BAGPIPES definition paper. They can be downloaded from .  You should copy the bc03_miles folder into the bagpipes/models directory.

### Usage

The code is not currently properly documented, for which I apologise and intend to correct as soon as possible. In the mean time however a series of example files are provided in the `examples` directory from which it is fairly simple to understand the usage of the code. The first two examples take you through making models, the third through loading data and the fourth through fitting models to data.

If you have any problems please contact me at adamc@roe.ac.uk.

![](examples/example_spectral_plot.pdf)
![](examples/example_corner_plot.pdf)