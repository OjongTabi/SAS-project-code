# SDTM to ADaM Data Transformation

This project involves transforming Study Data Tabulation Model (SDTM) lab data into an Analysis Data Model (ADaM) compliant dataset, specifically for LB (Laboratory Data) data.

## Process Overview

1. **Read in the SDTM lab data**: Load the SDTM LB dataset into the SAS workspace.

2. **Check dataset structure**: Use `PROC CONTENTS` to examine the structure of the SDTM LB dataset.

3. **Create the ADaM LB (ADLB) dataset**: Generate an ADLB dataset from the SDTM LB data.

4. **Variable retention and derivation**: Retain necessary variables for analysis and create derived variables for baseline and change from baseline.

5. **Flag significant changes**: Create a flag for significant changes from baseline.

6. **Apply ADaM metadata attributes**: This is a placeholder - actual metadata would be study-specific and would be applied based on the ADaM Implementation Guide.

7. **Quality Control**: Check SAS log for errors or warnings, and validate outputs. Ensure documentation for each step to maintain inspection readiness.

## Clinical Trial Data Import and Analysis

1. **Set the input data location**: Specify the path to the clinical trial data.

2. **Import the data into a SAS dataset**: Load the CSV data into a SAS dataset using `PROC IMPORT`.

3. **Check dataset structure**: Use `PROC CONTENTS` to examine the structure of the imported data.

4. **Data cleaning and manipulation**: Recode categorical variables, handle missing values, and create derived variables.

5. **Automate repetitive tasks**: Create a macro to automate tasks like generating summary statistics for a list of variables.

6. **Perform logistic regression**: Use `PROC LOGISTIC` to perform a logistic regression analysis.

7. **Quality Control**: Check SAS log for errors or warnings, and validate outputs. Ensure documentation for each step to maintain inspection readiness.

## Prerequisites
This project requires a solid understanding of SAS programming, SDTM and ADaM data standards, as well as familiarity with clinical trial data.

## Contributing
Contributors are expected to adhere to ADaM Implementation Guide and relevant regulatory guidelines. Please ensure thorough documentation for each step for reproducibility and inspection readiness.

## Author
Ojong Tabi

## License
This project is licensed under the MIT License.

## Acknowledgments
This work contributes to improving data transformation practices in clinical trial data analysis, and supports increased transparency and reproducibility.
