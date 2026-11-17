# adolescent-physical-activity-mental-health
This study examines the relationship between physical activity frequency and a spectrum of suicidal behaviors among adolescents in the United States. 

A standard analysis workspace for this dataset generally includes the following files:
analysis.Rmd: The primary R Markdown used
yrbs_data.csv (or .RData): The dataset containing the survey responses and variables.
analysis.html / analysis.pdf: The rendered output report generated after knitting the R Markdown file.

Centers for Disease Control and Prevention (CDC). Youth Risk Behavior Surveillance System (YRBS). Available from: https://www.cdc.gov/yrbs/data/

To successfully process the data and run the statistical models in the .Rmd file, you need the following libraries installed:
tidyverse: A collection of packages (including dplyr, ggplot2, and tidyr) to manipulate and visualize data.
broom: to convert statistical analysis objects (linear or logistic regression models) into tidy data frames.

You can install them by running this command in your R console if they aren't already installed: install.packages(c("tidyverse", "broom"))
