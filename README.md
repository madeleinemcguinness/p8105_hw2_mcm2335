# p8105_hw2_mcm2335

Added R Project Infrastructure

Added R Markdown File for HW2 completion

Changed output from html document to github document

Imported data tables into project & reknit to github document

Cleaned up 'pols_month' dataset to produce 'pols_month_final'
Steps: separated month variable, converted month numbers into month names, mutated new 'president' variable and deleted prez_gop, prez_dem, and day variables. Confirmed knit works correctly.

Cleaned up 'snp' dataset to produce 'snp_final' dataset.
Steps: separated date variable into 'year', 'month', and 'day' variables and arranged by 'year', 'month'. Confirmed knit works correctly.

Fixed up pols and snp datasets for consistency accross datasets (transformed year variable to be 4 digits instead of 2 digits and ensured that all year variables were of the same class for merging) and tidied the unemployment dataset. Merged all 3 data sets into 'combined_data_final.' Wrote inline R code but am having difficulty knitting.