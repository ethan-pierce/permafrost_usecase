# Data Component Use Case for Permafrost Thaw and Hillslope Diffusion
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/gantian127/permafrost_usecase/blob/master/LICENSE.txt)


This repository includes a [Jupyter Notebook](permafrost_alaska.ipynb) 
which demonstrates how to use several [CSDMS Data Components](https://csdms.colorado.edu/wiki/DataComponents) to download 
topography, snow and temperature data to calculate the permafrost active layer thickness 
and simulate the hillslope diffusion process for a study area in Alaska.

This Jupyter Notebook is part of the work for a research paper 
"CSDMS Data Components: data-model integration tools for Earth surface processes modeling".


### Notebook Citation
Gan, T., Tucker, G. E., Overeem, I., Pierce, E. (2023). 
Data Component Use Case for Permafrost Thaw and Hillslope Diffusion, HydroShare, https://www.hydroshare.org/resource/c4ebe3515a894446bf26aba0aedd7fdd/


### Run the Notebook
You can choose the following methods to run this Jupyter Notebook: 

#### Method 1: HydroShare
Please go to the [HydroShare Resource](https://www.hydroshare.org/resource/c4ebe3515a894446bf26aba0aedd7fdd/) 
and follow the instruction in the **"Abstract"** section to run this notebook.

#### Method 2: CSDMS
Please go to the [CSDMS EKT Lab](https://csdms.colorado.edu/wiki/Lab-0032) 
and follow the instruction in the **"Lab notes"** section to run this notebook.


#### Method 3: Local PC
Please first download all the files from this repository and have 
[conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) installed on the local PC.
Then, use the following commands to create a virtual environment and launch the Jupyter Notebook.
```
$ cd permafrost_usecase
$ conda env create --file=environment.yml
$ conda activate permafrost_usecase
$ jupyter notebook
```
