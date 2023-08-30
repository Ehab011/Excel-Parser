# Excel File Parsing and Data Validation

This script parses multiple Excel files in the current directory according to certain constraints as column names, API, and Date of production.

## Dependencies

- pandas
- os
- logging
- pathlib
- openpyxl
- re

## Usage

1. Place this script in the same directory as the Excel files you want to parse.
2. Modify the `COLUMN_MAPPING` dictionary to map the column names to standardized ones as per your requirements.
3. Run the script.
