# NCHS-Public-Use-Data-Munging

Pulling and processing into crunchable form public use files (PUFs) from data systems across NCHS, specifically:
* National Ambulatory Medical Care Survey (NAMCS)
* National Hospital Ambulatory Medical Care Survey (NHAMCS)

Data download sources: ftp://ftp.cdc.gov/pub/Health_Statistics/NCHS/dataset_documentation/namcs & /nhamcs

# Load survey and dplyr packages
library(dplyr)
library(survey)
options(survey.lonely.psu='adjust')

# Display Version Information
cat("R package versions:\n")


example of dataviz: https://jaredzun.shinyapps.io/CDC_Challenge_Suicide_Overdose_Trends/
