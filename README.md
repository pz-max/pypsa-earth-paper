# Article repo

**Title: PyPSA-Earth. A New Global Open Energy System Optimization Model Demonstrated in Africa**

**Paper: https://arxiv.org/abs/2209.04663**

The repository should help reproducing the results for the paper. Note that the PyPSA-Earth model is constantly evolving (and you can join). To reproduce the results for the paper you would need to use version [v.0.1.0](https://github.com/pypsa-meets-earth/pypsa-earth/releases/tag/v0.1.0).

Steps to reproduce the results:
1. Follow the installation requirements and instruction for [PyPSA-Earth](https://github.com/pypsa-meets-earth/pypsa-earth).
2. Move the here provided configurations to your local Earth model copy and name them `config.yaml`
3. For each config, execute the workflow (detailed in the PyPSA-Earth) with the command `snakemake -j1 solve_all_networks`
4. The plots to reproduce the all images are shared in the `notebooks` folder in `PyPSA-Africa/Earth`

Requirements:
- A user requires about 50GB disk space and about 16-32 GBRAM

## Useful links:
- [PyPSA meets Earth initiative website](https://pypsa-meets-earth.github.io/), to see about all our activities
- [PyPSA-Earth github page](https://github.com/pypsa-meets-earth/pypsa-earth), to run the model on the most updated version


![203567](https://user-images.githubusercontent.com/61968949/232501154-07a40a53-06db-4e20-895d-8a0dfa9595b1.png)
