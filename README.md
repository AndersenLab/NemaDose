# NemaDose
Experimental setup guide for HTA (V3) dose-response experiments using **serial drug dilutions**.
For a customizable drug exposure setup guide, see [HTA_dilutions](https://katiesevans9.shinyapps.io/HTA_V3_dilution/) by Katie Evans.

### Required R packages:
1. [R-tidyverse](https://www.tidyverse.org/)
1. [R-knitr](https://yihui.org/knitr/)
1. [R-kableExtra](https://cran.r-project.org/web/packages/kableExtra/vignettes/awesome_table_in_html.html)

### Protocol:
1. **Set working directory to the repo path**
2. **Verify drug stock sheet (`drug_stock_sheet.csv`) is updated with proper**:
* Stock concentration (mM)
* Highest dose in experiment (uM)
* Desired dilution factor for each drug
3. **Specify experimental factors:**
* Number of strains
* Number of replicates
* Number of doses
* Number of independent bleaches
* Excess percent to account for
4. **Specify drugs in experiment in `ChosenDrugList`**
5. **Press "Knit"**
6. **Verify resulting markdown is correct and print!**
