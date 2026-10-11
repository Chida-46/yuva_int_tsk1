# Titanic Dataset Data Cleaning and Preprocessing

## Project Overview
This project focuses on cleaning and preprocessing the Titanic dataset from Kaggle using Python and pandas in a Jupyter Notebook.

## Dataset Information
- **Dataset:** Titanic Training Dataset
- **Source:** Kaggle
- **Input file:** `train.csv`
- **Number of rows:** 891
- **Number of columns:** 12

## Tools and Technologies
- Python
- Pandas
- Jupyter Notebook
- Matplotlib
- Seaborn
- Visual Studio Code

## Data Cleaning Steps
1. Loaded the Titanic dataset using pandas.
2. Inspected the dataset structure, data types, and summary statistics.
3. Identified missing values in the dataset.
4. Filled missing `Age` values using the median.
5. Filled missing `Embarked` values using the mode.
6. Replaced missing `Cabin` values with `"Unknown"`.
7. Checked for duplicate rows.
8. Identified potential outliers in `Age`, `SibSp`, `Parch`, and `Fare` using the Interquartile Range (IQR) method.
9. Flagged and retained potential outliers for further review.
10. Exported the cleaned dataset to a CSV file.

## Results
- **Original dataset size:** 891 rows × 12 columns
- **Missing values before cleaning:** 866
- **Missing values after cleaning:** 0
- **Duplicate rows:** 0
- **Outlier treatment:** Identified and retained for review

## Project Files
- `train.csv` — Original Titanic training dataset.
- `organise_yuvas1.ipynb` — Jupyter Notebook containing the data cleaning process.
- `titanic_cleaned.csv` — Cleaned dataset exported from the notebook.

## How to Run the Project
1. Download the Titanic dataset from Kaggle.
2. Place `train.csv` in the project folder.
3. Open the folder in Visual Studio Code.
4. Open `organise_yuvas1.ipynb`.
5. Run the notebook cells in order.
6. Check the results and verify that missing values have been handled.
7. Find the cleaned CSV file in the `cleaned_output` folder.

## Install Required Libraries
Run the following command in the terminal if the libraries are not already installed:

```bash
pip install pandas matplotlib seaborn jupyter
```

## Conclusion
The Titanic dataset was cleaned by handling missing values, checking duplicates, and identifying potential outliers. The cleaned dataset contains 891 rows and 12 columns, with no missing values. Potential outliers were retained to avoid removing valid passenger records without further investigation.
