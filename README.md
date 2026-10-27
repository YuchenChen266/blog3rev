# Education Level, Unemployment Rate and Weekly Wages in the U.S. Labor Market
This repository contains descriptive analysis exploring how unemployment rate and weekly wages vary across education groups using IPUMS CPS data.

## Repository Structure
- `blog3.Rmd`: R Markdown source file, including analysis code and written discussion
- `blog3.html`: Rendered HTML file for GitHub Pages

## Replication Instructions
1. Go to IPUMS CPS website and create your own data extract with variables: EDUC, EMPSTAT, EARNWEEK, AGE, WTFINL
2. Download the extract (xml + dat.gz files) and put them into a local folder named `data/` on your own computer
3. Open `blog3.Rmd` inside RStudio
4. Install required packages if needed:
install.packages(c("ipumsr","tidyverse"))
5. Knit the document. All figures will be generated programmatically.
