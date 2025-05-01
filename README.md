# Cancer:The Timely and Deadly Disease

### Authors

**Manny Bettencourt**: Emory University

**Aryan Patel**: Emory University

**Aarush Bedi**: Emory University

## Project Objectives

Cancer has captured an increased presence in everyday conversations and its recent statistics are simply shocking. According to the Cancer Statistics, it was projected that about 2 million new cancer cases with 611,000 cancer deaths would occur in the United States in 2024 (Siegel et al., 2024). In order to understand how cancer’s impact is varied across the US, we identified the states in which new cancer cases occur most frequently and how often these cases result in death. We wanted our exploratory analysis to prompt further questions that the increase the resolution of the analysis like: **how do factors like cancer type and sex affect cancer incidence and mortality in US states with extreme rates?**

## Methods

- Sourcing Data from Emory's Library Databases  
- Distinguishing Variables and Their Types Within the Data  
- Restructuring the Data to Broaden the Scope of the Exploratory Analysis  
- Data Summary Tables  
- Data Visualizations Exploring Cancer Incidence and Mortality Rates  

## Languages/Platforms

- Language: R  
  - Packages: tidyverse, dplyr  
- Platform: R studio

## Project Description

### Research Questions

- How do cancer incidence rates vary across different states?  
- Are there observable trends in cancer incidence and mortality over time in the U.S.?

### Techniques and Visualizations

- Scatterplots for correlation and time series analysis  
- Histograms to visualize distribution

### Challenges

- The final merged data was acquired by doing a lot of preprocessing and merging, as the required information was not present in one simple dataset. For example, we had to manually go thorugh 50 different datasets, corresponding to each state and pick out the incidence and mortality statistics.  
- Due to changing population and statistics, we had some difficulties coming to the correct conclusions for what each mean rate truly meant.

### Potential Further Studies

Our exploratory analysis revealed that Utah consistently shows the lowest cancer incidence and mortality rates, while Maine and West Virginia have the highest. Future work could investigate the factors contributing to these trends and explore commonalities between states with higher rates.

## Instructions

1. Clone repository from GitHub
2. Open the .Rmd file in RStudio   
3. Set up R environment via 'renv' folder by running renv::restore  
4. Run the .Rmd file

## Directory Structure

├── Data/

│   ├── CancerIncidencebySexfromtheU.S.CancerStatisticsDataset.csv

│   ├── CancerMortalitybySexfromtheU.S.CancerStatisticsDataset.csv

│   ├── masterpopulationbystatesbysex.csv

│   ├── sc-est2019-agesex-civ.csv

│   └── sc-est2023-agesex-civ.csv

└── Report_and_Environment/

     ├── renv/

     ├── EDAProject.Rproj

     ├── EDAProjectonCancer.Rmd

     ├── EDAProjectonCancer.html

     └── renv.lock


