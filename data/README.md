## Data ##

The data folder includes all data used in the final paper. The data has been cleaned.

The original folder contains all the data before processing.

### Replication steps ###

1. Go to `./original_data/Boix_Miller_Rosato`
    * run `BMR_process.ipynb`
    * the output is `cleaned_BMR.csv` saved to the directory

2. Go to `./original_data/Freedom_House`
    * run `FH_process.ipynb`
    * the output is `cleaned_FH.csv` saved to the directory

3. Go to `./original_data/VDEM`
    * you need to download the Country-Year: V-Dem Full+Others data set from [VDEM website](https://www.v-dem.net/en/data/data-version-9/). Save it in the VDEM directory. The data set is too large to put on Github.
    * run `VDEM_process.ipynb`
    * the output is `cleaned_VDEM.csv` saved to the directory

4. Go to `./Intermediate_data_processing`
    * copy all the cleaned_* output files that have just been processed to this directory
    * run `data_merge.csv`
    * the output is `democracy.csv`

5. Copy `democracy.csv` to `./fp-sanittawan/output`

6. Go to `./fp-sanittawan/output` run `analysis.ipynb`
