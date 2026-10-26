# M1: Reproducibility Plan

## Expected Repository Structure

The project will use the following folders:

- data/- Contains the WHO hospital beds CSV file or a documented method to access it.
- report/ - Contains the Quarto report and analysis code.
- dashboard/ - Contains the Quarto dashboard source files.
- milestones/m1-proposal/submission/ - Contains the five required M1 proposal files.

## Data Access Plan

The dataset will be obtained from the WHO Global Health Observatory website.

Source:
https://www.who.int/data/gho/data/indicators/indicator-details/GHO/hospital-beds-%28per-10-000-population%29. 

Plan to download the public indicator data as a CSV file and store it in the data/ folder if its size and reuse terms allow.

The source URL, download date, and any cleaning steps will be documented.

If the full dataset is too large or cannot be redistributed, I will document how to obtain it instead of committing the full file.

## Software and Dependencies

The analysis will be completed in R using the course GitHub Codespaces environment.

Expected packages include:

- tidyverse for importing, cleaning, and summarizing data.
- ggplot2 for creating visualizations.
- quarto`for creating the report and dashboard.

The required software versions and any additional packages will be documented as the project develops.

## Reproduction Steps

Another student should be able to reproduce the analysis by:

1. Opening the GitHub repository in the course Codespace.
2. Obtaining the WHO dataset using the documented source.
3. Placing the CSV file in the data/ folder.
4. Running the R code in the report from the repository root.
5. Rendering the Quarto report and dashboard using the documented commands.
6. Comparing the generated tables and figures with the submitted outputs.

All scripts will use relative paths rather than local computer-specific file paths.

## Feasibility

The WHO dataset is publicly accessible and provides an aggregated numerical indicator suitable for descriptive analysis.

The proposed project uses country comparisons, summary statistics, and basic visualizations that can be completed using R and the tools introduced in the course.

The CSV has not yet been imported or checked in R. We will confirm the available countries, years, column names, missing values, and file size before beginning the analysis.

The final selection of countries and years will depend on data availability.

