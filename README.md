# Blog 3: Education, Unemployment and Weekly Earnings in the U.S. Labor Market
This repository reproduces the descriptive analysis of IPUMS CPS labor market data.

## Repository Structure
- `blog3.Rmd`: R Markdown source file, full code and written blog text
- `blog3.html`: Rendered HTML webpage for GitHub Pages
- `data/`: Contains the IPUMS CPS extract `cps_00003.xml` and microdata file
- `figures/`: Auto-generated plot outputs

## Replication Instructions
1. Download the IPUMS CPS extract and place the .xml and .dat file inside the `data/` folder
2. Open `blog3.Rmd` in RStudio
3. Install required packages:
install.packages(c("ipumsr","tidyverse","haven"))
