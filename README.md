# Differential morphospace occupation patterns of terrestrial and aquatic gastropods


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7878281.svg)](https://doi.org/10.5281/zenodo.7878281)



## Files

* notebooks
    * generatemodel.ipynb
    * fuctionalities.ipynb
* pyproject.toml
* README.md

### Notebooks
#### generatemodel.ipynb
In this notebook, we created a theoretical morphological model of gastropods with Raup's logarithmic shell coiling model.  
We approximated models using a voxel-based approach, of which avoxel is segmented into shell/soft-body regions.   
The voxel is discretized by the length of one side of the shell width divided into 170 segments.

#### fuctionalities.ipynb
We calculated two functional indicators: N is the norm of the vector from the fulcrumpoint to the center of mass of the shell, and S is the projected area.

## Installation and Usage
Download this repository and install dependencies with poetry.

```sh
git clone https://github.com/MorphometricsGroup/Araki_2023.git

cd Araki_2023

poetry install --no-root
```

Then, launch Jupyter Lab for opening each notebook.

```sh
poetry run jupyter lab
```

## License
These supplementary materials are licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) License.
