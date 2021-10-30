# Assisted living data

Data and code for NeurIPS MLPH 2021 extended abstract *Assisted Living in the United States: an Open Dataset*

Dataset of assisted living facilities is `alf-dataset.csv`. It has data from all 50 states + DC.

Brief description of the repo:
- `notebooks` contains most of our code used to process, clean, and analyize the data. File paths are somewhat broken due to rearranging file structure.
- `data` contains additional data files. 
  -  `raw-state-data` contains the raw data gathered from all of the 50 states + DC, as well as different stages of processing for each state's data.
  - `county-data-for-replication` contains tables gathered from ACS data to replicate the past ALF study.
  - `other-data` contains an assortment of other data files used throughout the process.
