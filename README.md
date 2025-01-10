# fleet-optimization
### Description

This project focuses on preprocessing and standardizing data from multiple CSV files related to fleet optimization. The goal is to prepare the data for further analysis by cleaning, transforming, and merging various datasets into a single comprehensive DataFrame.

### Key Features:

Data Loading: The project begins by loading multiple CSV files containing fleet data into separate pandas DataFrames.
Column Standardization: A function is implemented to standardize column names by converting them to lowercase and replacing spaces and special characters. This ensures consistency across all datasets.

Column Dropping: Unnecessary columns are identified and removed from the DataFrames to streamline the dataset.
Distance Value Cleaning: A dedicated function cleans the distance values, extracting numeric parts and their respective units (Kilometers or Miles) while handling any erroneous entries gracefully.

Data Merging: Finally, all cleaned DataFrames are combined into a single DataFrame, ensuring that all columns are present and filled with NaN where necessary.

### Technical Details:


Programming Language: Python
Libraries Used:

pandas: For data manipulation and analysis.

numpy: For numerical operations and handling missing values.

### Output:

The final output is a combined DataFrame containing standardized and cleaned data, ready for analysis or machine learning applications. The shape of the combined DataFrame is (5833, 12), indicating it contains 5833 rows and 12 columns.


### Usage:

To run this project, ensure that all required libraries are installed, and the specified CSV files are accessible at the given paths. Execute the provided code in a Python environment to preprocess the data. This README provides a comprehensive overview of your project, outlining its purpose, features, technical details, and usage instructions. Adjust any sections as necessary to better fit your project's specifics or personal style.
