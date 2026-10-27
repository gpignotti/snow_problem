# Analysis code for:


> 'SNOW PROBLEM? INFLUENCES OF SNOWPACK ON SPRING AND SUMMER STREAM TEMPERATURES AND STREAMFLOW IN THE WESTERN CASCADES, OREGON' *Water Resources Research*. https://doi.org/[DOI]

The code reproduces the data processing, statistical analyses, and Figures of the paper. It examines how interannual snowpack variability (water years 1999–2018) relates to spring and summer stream temperature and streamflow in four nested watersheds of the Lookout Creek basin, western Cascades, Oregon.

## Data

The raw data are not redistributed here. They are published by the H.J. Andrews Experimental Forest LTER through the Environmental Data Initiative (EDI):

| Data | Package | Citation | DOI |
|------|---------|----------|-----|
| Streamflow | HF004 | Johnson et al. (2025) | https://doi.org/10.6073/pasta/9826b79c5bb9e80e37c08c02b2ee13f6 |
| Stream and air temperature | HT004 | Johnson et al. (2026) | https://doi.org/10.6073/pasta/4d0e647de6e461c29ff13456849ea328 |
| Snow | MS001 | Levno et al. (2026) | https://doi.org/10.6073/pasta/dbb52557c9fd40cf78c6c44ad86be484 |
| Precipitation | MS001 | Schulze et al. (2026) | https://doi.org/10.6073/pasta/c30028e97bf7ec5be4fb72d08ab64bd2 |

Full citations are in the paper's reference list.

## Scripts

| Step | Script | Produces |
|------|--------|----------|
| 1 | `01_process_hja_data.Rmd` | Read in data and process for analysis, including handling bad or missing data |
| 2 | `02_site_map_hypsometry.Rmd` | Figure 2 panels; watershed elevation and aspect tables |
| 3 | `03_analysis_and_figures.Rmd` | Figures 3–11, S1–S4; supporting tables |


## License

Code is released under the MIT License (see [LICENSE](LICENSE)). The data are subject to the terms of the original EDI packages.

## Citation

If you use this code, please cite the paper and the archived release (see [CITATION.cff](CITATION.cff)).

## Contact

Garett Pignotti — gpignotti@gmail.com
