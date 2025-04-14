# EDA-Analysis-Tools
 Tools for quick exploratory data analysis (EDA) of numeric and categorical columns in pandas DataFrames.
This repository contains reusable Python functions to perform exploratory data analysis (EDA) on tabular data using pandas, seaborn, and matplotlib.
## Functions
- `analyze_numeric_column(df, column_name, target='Survived')`
- `analyze_categorical_column(df, column_name, target='Survived')`
## Example
```python
from eda_tools import analyze_numeric_column, analyze_categorical_column
analyze_numeric_column(df, 'Fare')
analyze_categorical_column(df, 'Embarked')
