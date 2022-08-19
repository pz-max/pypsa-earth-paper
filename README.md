# pypsa-earth-paper

Steps to reproduce the results:
1. Follow the installation requirements and instruction for PyPSA-Africa/Earth
2. Move the here provided configurations to your local Africa/Earth model copy and name them `config.yaml`
3. For each config, execute the workflow (detailed in the PyPSA-Africa/Earth) with the command `snakemake -j1 solve_all_networks`
4. The plots to reproduce the all images are shared in the `notebooks` folder in `PyPSA-Africa/Earth`

Requirements:
- A user requires about 50GB disk space and about 16-32 GBRAM
