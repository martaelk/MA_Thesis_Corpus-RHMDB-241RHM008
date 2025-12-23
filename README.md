# Introduction
This repository contains the data, preprocessing steps, and visualizations used in a Master's Thesis "Visualising Notated Music Metadata from the Latvian National Bibliography" conducted within the RTU studies program RHMDB Digital Humanities.
The author of the Master Thesis is Marta Elizabete Kivkule; identity card number is 241RHM008.
## Repository structure
- `data_raw/` – raw exported metadata from union catalogue Kopkatalogs in Aleph Sequential format
- `data_clean/` – cleaned and processed datasets
- `openrefine/` – OpenRefine transformation history
- `notebooks/` – GoogleColab notebooks for analysis and visualization
- `scripts/` –  Python scripts corresponding to individual analytical segments of the thesis, including data quality checks, temporal analysis, network construction, and MARC field exploration.
- `output/` – generated figures and tables in png format
- `data_quality/` – automatically extracted and manually documented metadata issues identified during analysis.

## Reproducibility
1. Clone the repository.
2. Install dependencies listed in `requirements.txt`.
3. Open `notebooks/visualisations_mg.ipynb` in Jupyter or Google Colab.
4. Run all cells to reproduce the results.

Alternatively, individual analytical steps can be reproduced by running the individual Python scripts located in the `scripts/` directory.  
These scripts are modular and can be executed independently, as each script loads the prepared dataset and performs a self-contained analysis
