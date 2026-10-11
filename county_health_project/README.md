# County Health Outcomes and Socioeconomic Conditions

Milestone 1 by Dylan Sawransky.

Open `county_health_milestone.ipynb` in Jupyter or Google Colab. It includes executed outputs, the project plan, light ETL, five exploratory summaries, and a chart. Replace the collaboration paragraph and repository link with your actual information before submitting.

## Run locally

Install `pandas numpy matplotlib` and run the notebook from this folder. Raw snapshots and cleaned data are included. Colab users should upload/extract the project folder and change their working directory to it before running the cells.

## Files

- `county_health_milestone.ipynb`: notebook with outputs
- `data/places_2025.csv`: CDC PLACES snapshot
- `data/chr_2025.csv`: CHR 2025 analytic snapshot (two header rows)
- `data/county_health_cleaned.csv`: merged, tidy county table
- `figures/income_diabetes.png`: scatterplot

## Sources

https://data.cdc.gov/500-Cities-Places/PLACES-County-Data-GIS-Friendly-Format-2025-releas/i46a-9kgh
https://www.countyhealthrankings.org/health-data/methodology-and-sources/data-documentation
https://www.cdc.gov/places/methodology/index.html

Snapshots retrieved October 10, 2026. CHR download: https://www.countyhealthrankings.org/sites/default/files/media/document/analytic_data2025_v3.csv?download=1
CDC API: https://data.cdc.gov/resource/i46a-9kgh.csv?$limit=10000

These are observational county data and modeled prevalence estimates. The notebook describes limitations, missingness, and planned predictive validation.
