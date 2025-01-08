# Project - Data Profiling and Preparation

## Description
This project involves performing data profiling and cleansing on the Passenger Satisfaction Survey dataset. The goal is to examine, assess, and clean the dataset to address technical and data issues using Python. The final outputs include a cleaned dataset in CSV format and a Jupyter Notebook documenting the entire workflow.

---

## Key Tasks
### 1. Data Access and Profiling
- Load the Passenger Satisfaction Survey dataset into a pandas DataFrame.
- Create a subset containing only Business Class passenger data (`df_Business`).
- Collect the following information:
  - Number of observations and variables.
  - Column names, data types, and unique values.
  - Count of missing values for each column.
  - Summary statistics for numerical columns.
  - Frequency distributions for categorical columns.
  - Count of fully duplicated rows.
- Document identified data issues.

### 2. Data Cleansing
- Drop the `Class` column from `df_Business`.
- Rename all columns to lowercase and replace spaces with underscores.
- Correct improperly formatted data and handle inconsistencies.
- Address missing values (ensuring zero missing entries in the cleaned dataset).
- Remove fully duplicated rows.
- Fix column data types to match the correct formats.
- Export the cleaned dataset to a CSV file.

### 3. Comparison of Data Characteristics
- Compare column attributes before and after cleansing, including:
  - Column names.
  - Data types.
  - Unique values.
  - Number of missing values.

---

## Technologies Used
- **Programming Language:** Python
- **Tools and Libraries:**
  - Pandas
  - NumPy
  - Jupyter Notebook

---

## Outputs
1. **Cleaned Dataset:**
   - A CSV file containing the cleaned data.

2. **Jupyter Notebook:**
   - Fully annotated notebook showcasing:
     - Data profiling.
     - Data cleansing steps.
     - Comparison of data characteristics before and after cleansing.

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/VijayAtheli1709/Project_Data_Profiling.git


Install required libraries:
bash
Copy code:
pip install pandas numpy jupyter

Open the Jupyter Notebook:
bash
Copy code
jupyter notebook Data_Profiling_Preparation.ipynb

Project Highlights:
Demonstrates advanced skills in data profiling and cleansing.
Utilizes Python for real-world data preparation tasks.
Includes comprehensive documentation for reproducibility.
