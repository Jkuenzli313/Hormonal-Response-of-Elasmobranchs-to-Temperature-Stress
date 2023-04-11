# Objective:
## The purpose of this experiment was to develop a new baseline for determining a sex hormone concentrations of Atlantic stingrays (Hypanus sabinus) throuhout the reproductive cycle, as well as elucidate the effects of temperature on the sex hormone concentrations. 
# Structure of Code:
## All data is in a csv file, script in Rmd files, and figures in png format.
## Meta Data Structure:
### Month Data: Each column represents the concentration of each sex hormone in pg/mL per each month of sample. The numbered row represents how many samples were available for each month.
### Temperature Data: Each column represents the concentrations of testosterone in pg/mL for each ray in their respective temperature groups (16C, 21C, and 26C). The numbered row represents how many samples were available for each temperature group. 
# Steps for reproducing results:
## Read in data files, restructure data into longer format, produce linear models for each data set, use lm models to generate anovas to look for significance, and finally generate box-plots for each data set.
