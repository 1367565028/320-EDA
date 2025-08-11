# EDA Code Notebook

This project is the EDA notebook project for the QTM302w course taught by Dr.Palermo during the summer 2025 semester.

## Contributors

Leila Buchan  
Alexandra Brown   
Michael Zhao  

## Project Intro/Objective

The purpose of this project is to analyze how the job market responds to different crises and the long-term trend of the job market. In order to analyze the response, the project focuses on the change of unemployment over time and during the 2 periods.

### Methods Used

* Inferential Statistics
* Data Visualization
* Data Cleaning

### Technologies

* R 
* HTML


## Project Description

This Project is based on R. The project uses 1 dataset of monthly civilian unemployment rates from 1990 to 2025. Includes introduction, data cleaning and modification, data visualization, summary stats, and conclusion. The project specifically focuses on the unemployment rate during the Great Recession (2006-2014) and the COVID-19 pandemic (2019-2024). The data has been modified, transformed into central tendencies, and visualized in line plots and heatmaps. The two periods are compared, and the project includes the identification of patterns in unemployment spikes and recoveries. The finding of the project is unemployment rate rises and falls in a cyclical pattern, but each cycle would perform differently based on different geopolitical and financial factors during the period.

## Challenges

1. Narrow scope: The project mainly focuses on 2 short time periods, rather than a general timeline, the observations may not be really general enough to conclude the pattern of the job market for the long term.
2. Missing Interpretation: The Project didn't focus on causality factors but only the plots; some of the causality factors have not been tested.

## Future Steps

1. Focus on different regions responding to the crisis differently.
2. Apply economic models to geopolitical factors to test the relationship between them and the unemployment rate.
3. Focus on how groups with different Demographic identities respond.

## Getting Started

1. Clone this repo.  
2. Raw Data is being kept in `data` folder, `SeriesReport1990-2025.xlsx` includes the data from the US Bureau of Labor Statistics(https://data.bls.gov/timeseries/LNS14000000?).  
3. Rmd file is being kept in `EDA` folder, it has all the code for the project.
4. HTML report is being kept in `docs` folder, it is rendered from the Rmd file.
5. Required packages have been kept with `renv`

## Directory
.
└── 320 EDA/
    ├── EDA/
    │   └── EDAUnemployment.Rmd
    ├── data/
    │   └── SeriesReport1990-2025.xlsx
    ├── docs/
    │   └── EDAUnemployment.html
    ├── renv/
    │   ├── .gitignore
    │   ├── activate.R
    │   └── settings.json
    ├── .Rprofile
    ├── .gitignore
    ├── 320 EDA.Rproj
    ├── README.md
    └── renv.lock
    
## Contact

* Leila's email: leila.buchan@emory.edu  
* Alex's email: alexandra.brown@emory.edu  
* Michael's email: michael.zhao@emory.edu









