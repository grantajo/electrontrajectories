# Electron Trajectories

This code takes electron trajectories simulated using CASINO and performs calculations relating to energy deposition and trajectory mapping.

This code also uses that energy deposition information in informing two modeling/simulation frameworks for modeling melt pool depth.
- Cylindrical axisymmetric finite difference model for spot melting
- Eagar-Tsai moving heat source model (To be done in future.)

## Running this code

### Create a virtual environment

Conda:

`conda create --name "myenv"`

`conda activate "myenv"`

`conda install "list of dependencies"`

### Installing this repository

`git clone https://github.com/grantajo/electrontrajectories.git`

### Required dependencies

- Numpy: `conda install `
- Pandas: `conda install pandas`
- Scipy: `conda install scipy`
- Matplotlib: `conda install matplotlib`
