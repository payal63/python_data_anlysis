# Data Cleaning Using Python

This README file provides an overview of the data cleaning process performed using Python. Below are the steps and methods implemented to clean and standardize the dataset.

## Steps for Data Cleaning

1. **Removing Duplicate Values**
   - Utilized the `drop_duplicates()` method to eliminate duplicate rows from the dataset.

2. **Standardizing Column Names**
   - Applied consistent naming conventions to column headers for better readability and uniformity.

3. **Removing Extra Spaces and Special Characters**
   - Used the `strip()` function to remove unwanted spaces and special characters such as `..`, `,`, `/`, and `-` from text data.

4. **Retaining Numeric Characters Only**
   - Employed the `replace()` function with a regular expression to remove all characters except numeric values in relevant columns.

5. **Standardizing Phone Numbers**
   - Applied a lambda function to format phone numbers into a consistent pattern, ensuring data uniformity.

6. **Dropping Rows with "Do Not Contact" Marked as Yes**
   - Iterated through rows using a `for` loop and removed any rows where the "do not contact" field was marked as "yes."


## Requirements

- Python 3.x
- pandas library

## Usage

1. Replace `data.csv` with the path to your dataset.
2. Update column names (`column_name`, `numeric_column`, `phone_number`, etc.) to match your dataset.
3. Run the script to clean and save the dataset.

## Output

The cleaned dataset will be saved as `cleaned_data.csv`. Ensure to verify the output for any inconsistencies.
