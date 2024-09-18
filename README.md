[![DOI](https://zenodo.org/badge/844590435.svg)](https://zenodo.org/doi/10.5281/zenodo.13773209)

This repository contains code to recreate the figures from "Limiting hearing loss in transgenic mouse models" by Babola, Donovan, Darcey, and Kanold (2024-ish). Each figure is broken into it's own folder, with subsequent panels indicated in the file name.

In order to succesfully recreate figures, the corresponding data can be downloaded [here](https://zenodo.org/doi/10.5281/zenodo.13761405) and placed within the repository to run properly. If a custom location is desired, this can be specified in the [config file.](/Code/Travis/config.py).

### Using this library
#### 1. Download repository and install dependencies
```
git clone https://github.com/tbabola/Cdh23.git
cd Cdh23
conda create -n Cdh23 python==3.10
pip install -r requirements.txt
```

#### 2. Download data
Download from [here](https://zenodo.org/doi/10.5281/zenodo.13761405) and place within the repository to run properly. Otherwise, change path in [config.py file](/Code/Travis/config.py).


   