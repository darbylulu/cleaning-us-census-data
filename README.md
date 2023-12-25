# Portfolio Project: Cleaning and Analyzing US Census Data

## Overview
This project involves a detailed analysis and cleaning of the US Census dataset. The goal is to prepare the data for insightful analysis by addressing issues such as incorrect data types, misplaced symbols, and missing values.

### Key Steps in the Project

#### Data Examination
- Initial examination of columns and data types in the `us_census` DataFrame.
- Identification of data type inconsistencies and potential cleaning needs.

#### Data Cleaning
1. **Cleaning the Income Column**: 
   - Removal of dollar signs and commas from the `Income` column using regular expressions (regex).
   - Conversion of the cleaned column to a numeric data type for further analysis.

2. **Splitting the GenderPop Column**:
   - The `GenderPop` column contained combined data for men and women's population. 
   - Application of `str.split` method to segregate this data into separate `Men` and `Women` columns.
   - Removal of `M` and `F` characters for clarity and consistency.

3. **Handling Missing Values**:
   - Identification and imputation of missing values in the `Women` column.
   - Estimation strategy based on the total population and men's population for each state.

### Goals of the Analysis
- To ensure data integrity by cleaning and transforming the dataset.
- To provide a clean dataset that can be used for various analytical purposes, such as demographic studies, policy-making, and socio-economic research.

## Tools and Libraries Used
- Python for data manipulation and analysis.
- Pandas for DataFrame operations and handling.
- Regular expressions for data cleaning.

## How to Use
- Clone the repository.
- Open the Jupyter Notebook to view the analysis and cleaning steps.
- The cleaned dataset is available for further analysis and exploration.
