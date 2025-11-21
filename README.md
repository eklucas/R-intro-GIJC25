# R-intro-GIJC25
Materials for Intro to R Programming (Parts 1 and 2) at GIJC in Kuala Lumpur

### Installing R and RStudio
Install both R and RStudio on your own computer using these instructions:[https://bit.ly/ire-install-r](https://bit.ly/ire-install-r)

You can also create an account with [Posit.Cloud](https://posit.cloud) and use RStudio through your browser (without installing anything on your computer) but the free account has some limitations (size of data you can process, how many projects you can create, etc). 

Install the necessary packages for this material by running this code in the RStudio console (you only need to do this once on your computer):\
`install.packages(c("tidyverse","janitor","readxl","googlesheets4"))`

### Finished Scripts: 
You can find complete and annotated scripts for the main concepts in the /scripts folder. 

### Datasets:

-   **Population by country, literacy, age, sex and urban/rural residence** (from the UN)\
[Source](https://unstats.un.org/unsd/demographic-social/products/dyb/index.cshtml#censusdatasets)\
Link for import: `https://github.com/eklucas/R-intro-GIJC25/blob/main/data/UN_literacy.csv`

-  **Eurovision** (created by my former student Mariia Novoselia)\
[Source](https://github.com/mariianov/ADJ_final)\
Link for import: `https://github.com/eklucas/R-intro-GIJC25/raw/refs/heads/main/data/Eurovision.csv`

-  **Poverty in the United States** (by state and county)\
[Source](https://data.census.gov/table/ACSST5Y2023.S1701)\
Link for import: `https://github.com/eklucas/R-intro-GIJC25/raw/refs/heads/main/data/US_poverty.csv`

-  **US Federal Campaign Transactions** (for independent expenditures)\
[Source](https://www.fec.gov/data/browse-data/?tab=bulk-data)\
Link for import: `https://github.com/eklucas/R-intro-GIJC25/raw/refs/heads/main/data/transactions.csv`

### Tipsheets: 
You'll find useful "cheatsheets" for Tidyverse packages along with some helpful tipsheets I created on R Functions, an R dictionary, a guide for newsroom math (created by Steve Doig)