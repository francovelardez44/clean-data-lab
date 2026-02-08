# Data Cleaning Notes

## Dataset overview
This dataset contains basic customer information, including client ID, name, email, service type, status, and date.

The original dataset was reviewed and cleaned to improve consistency, readability, and data quality while preserving all valid records.

## Issues identified in the raw dataset
- Inconsistent values in the `status` column (mixed labels and unclear categories)
- Date values stored as text with inconsistent formatting
- Presence of missing or unclear values in some fields
- Email addresses requiring format validation
- Inconsistent capitalization in text fields

## Cleaning actions taken
- Standardized the `status` column to consistent values (`Active` / `Inactive`)
- Reviewed and validated all email addresses to ensure correct structure
- Ensured consistent text formatting across categorical fields
- Reviewed all records to confirm data completeness
- Preserved all valid records after validation

## Date handling
- Dates were reviewed and standardized to a consistent format (DD/MM/YYYY)
- No records were removed due to date issues
- All date values were retained after validation

## Assumptions and decisions
- All records were considered relevant and kept after validation
- Status values were normalized to improve clarity and consistency
- The dataset was cleaned without removing records, focusing on standardization rather than reduction

- Status values were normalized to improve consistency
- No records were deleted unless they were duplicates or clearly invalid
