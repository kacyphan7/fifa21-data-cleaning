# Python Data Cleaning Using FIFA21 Dataset 
## Introduction
This repository encompasses the code and documentation for a comprehensive data cleaning project focused on the FIFA21 dataset. The primary objective of this project is to refine and enhance the dataset, which contains information about players featured in the popular FIFA21 video game.

## Language and Libraries Used
The data cleaning project relied on a suite of tools and libraries to facilitate the process:

- NumPy: Employed for mathematical operations and array manipulation during the cleaning process.
- Jupyter Notebooks: Provided an interactive environment for code development, data exploration, and documentation.
- Pandas: Instrumental for data manipulation, cleaning, and handling missing values.
- Python: Utilized for data cleaning tasks.

### Data Issues
During the initial exploration and analysis of the FIFA21 dataset, several data issues came to light, including:

1. Missing Values: Notably, the 'Free' and 'Loan Date End' columns contained missing values that required meticulous handling and computation.

2. Inconsistent Formatting: Inconsistent formatting was observed across different columns, necessitating the standardization of data for uniformity. For instance, the 'Heights' and 'Weights' columns contained values stored in varying units.

## Data Cleaning Process
The data cleaning process was executed through a series of structured steps:

1. Data Understanding: A comprehensive examination of the dataset to understand its structure, columns, and their meanings. This step also involved identifying data issues such as missing values and inconsistent formatting.

2. Data Exploration: Exploratory Data Analysis (EDA) was conducted to gain insights into the data, identify patterns, and uncover anomalies.

3. Handling Missing Values: EDA revealed the presence of missing values in the 'Free' and 'Loan Date End' columns. Further analysis demonstrated that these missing values were logical. The 'Loan Date End' column indicated when the contracts of players on loan would end. As some players were 'Free' agents while others were under contract, their records were appropriately left blank.

4. Standardizing Formatting: To address inconsistent formatting issues, such as values in the 'Heights' and 'Weights' columns stored with different units, transformations, lambda functions, and data normalization techniques were applied.

5. Validation and Quality Checks: The cleaned dataset underwent stringent validation to ensure the quality, accuracy, and integrity of the data.

This data cleaning project enhanced the FIFA21 dataset, making it more reliable and ready for in-depth analysis. The resulting dataset provides a solid foundation for further research and insights into the world of FIFA21 player statistics.

