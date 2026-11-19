# Treated blood pressure dataset, NHANES 2021 to 2023

The R Markdown file builds a dataset of adults taking blood pressure medication from NHANES (August 2021 to August 2023), ready for a logistic regression of what is linked to uncontrolled blood pressure. Uncontrolled means an average reading of 140/90 mmHg or more, or 150/90 mmHg or more from age 80 (NICE).

## Running it

To run it, please open HDS_M1_NICHOLASHALE_2611.Rmd in RStudio and click Knit. You need an internet connection, as the NHANES files download from the CDC website. Missing packages install themselves.

## Files

- HDS_M1_NICHOLASHALE_2611.html: the report
- treated_bp.csv: everyone on treatment, with exclusion flags
- ard.csv: the analysis ready dataset
- data_dictionary.csv, dataset_metadata.csv and phenotypes.csv: the metadata
- coversheet1.png to coversheet3.png: the coversheet pages shown in the report

Knitting recreates the CSV files.

Nicholas Hale
