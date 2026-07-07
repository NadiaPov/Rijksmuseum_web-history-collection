# Rijksmuseum_web-history-collection
Analysis of web-archived records of the Rijksmuseum's website
## Overview
This repository collects the Jupyter notebooks and selected research outputs developed for my research on the **web-archived presence of the Rijksmuseum**. The notebooks extract data from the **Internet Archive (Wayback Machine)** and also compare those results with **Rijksmuseum data dumps**. Together with the computational workflow, the repository includes ** some derived and processed datasets** and **visualisations** produced during the analysis, with the aim of making the work transparent and reusable for digital humanities research.

## Contents
- **Jupyter notebooks (Python)** for:
  - retrieving and parsing Internet Archive captures,
  - cleaning and normalising extracted information,
  - aligning fields and comparing against Rijksmuseum data dumps,
  - producing tables and visualisations.
- **Research outputs**, including processed datasets and figures/charts (where sharing is permitted).

## Data sources
- **Internet Archive / Wayback Machine**: https://web.archive.org/
- **Rijksmuseum Historical data dumps**: https://data.rijksmuseum.nl/docs/data-dumps/historical-dumps

This repository does **not** include data from the **Dutch web archive** due to copyright/access restrictions.

## Data derivatives
Research outputs are published on Zenodo: Povroznik, Nadezhda (2026) Rijksmuseum Web Presence in the Internet Archive: Research Datasets 1999–2025, https://zenodo.org/records/21134681

## Reproducibility
To reproduce the research process, the following steps are needed:
1) clone the repository on GitHub or download the files (keep the structure of the folders as it is in the repo);
2) download datasets published on Zenodo to the data folder;
3) check the paths indicated in the notebooks, make sure you have the files in the right folders, and run the code.

## License
- **Code (notebooks/scripts): MIT License** (see `LICENSE`)
- **Documentation & original visualisations: CC BY 4.0** (see `LICENSE-CC-BY`)

## Relationship to the paper
This repository accompanies the paper (**JDH**) and provides the computational record for the extraction, processing, and comparison steps.
