# Assisted living dataset

This repository contains the first national dataset of assisted living facilities in the United States, covering over 44,000 facilities from all 50 states and the District of Columbia.

Along with the final dataset, the repository contains Python scripts used to gather, clean, and analyze the data. Additionally, the repository contains all the raw data gathered from each state's licensing agencies.

The project is in the process of being published at the NeurIPS MLPH 2021 Machine Learning in Public Health conference in mid-December as *Assisted Living in the United States: an Open Dataset*. When this happens, we will provide a link to the extended abstract, which gives much more detail as to how "assisted living" was defined, how the data was collected, and more.

The dataset of assisted living facilities is `alf-dataset.csv`.

Brief description of the repository:
- `notebooks` contains most of our code used to process, clean, and analyize the data. File paths are somewhat broken due to rearranging file structure.
- `data` contains additional data files. 
  -  `raw-state-data` contains the raw data gathered from the 50 states + DC, as well as different stages of processing for each state's data.
  - `county-data-for-replication` contains tables gathered from ACS data to replicate past assisted living studies.
  - `other-data` contains an assortment of other data files used throughout the process, including a few fun graphics.
