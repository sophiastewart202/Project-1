# Vaccines and Adverse Reactions
## Data Overview
This project examined reported adverse reactions by vaccine type from the Vaccine Adverse Event Reporting System (VAERS), a CDC and FDA project used to monitor trends and detect potential problems with vaccines or vaccine lots.

The VAERS system data have many limitations including (but not limited to), underreporting, reporting of adverse events even if cause is unclear or unlikely to be caused by a vaccine, missing data from reports, data entry errors, and a 20x or greater increase in reporting for COVID-19 relative to other vaccines in previous years.

## Project Description
Our project focused on quantifying adverse reactions by various vaccine types, notably for COVID-19. Multiple analysis were conducted with the data to discern trends from the VAERS data set that might have meaningful implications. This included graphing adverse reaction type by age, gender, US state, and plotting select time series characterizations.

## Link to Project
https://github.com/sophiastewart202/Project-1

## Code
Code found in repository files.

## Charts
Charts found in repository files.

## Presentation
Copy of presentation (as pdf) in Resources/docs folder.

## Raw, Merged, and Cleaned Data Files
Due to GitHub file size limitations, all data files are stored externally in a Google Drive folder:

https://drive.google.com/drive/folders/1hwTa6RAzUPnXDnNFz6Gnx6cgbTB0OUi-?usp=sharing

To reconstruct the reposity, first clone the reposity, then download the three zip files from the folders in the Google Drive link and unzip them in the following folders:

1. raw/raw.zip --> Resources/raw
2. aggr/aggr.zip --> Resources/aggr
3. clean/clean.zip --> Resources/clean

## Data Sources
VAERS data: https://vaers.hhs.gov/data/datasets.html

* VAERS Data Use Guide in Resources/docs folder.

Additional supporting data for geographic analysis (files in Resources/clean folder):
* US Census Bureau Regions and Divisions: https://www2.census.gov/geo/docs/maps-data/maps/reg_div.txt
* State populations: https://worldpopulationreview.com/states
* Percent population in each state receiving at least one COVID-19 dose: https://ourworldindata.org/covid-vaccinations
