# Introduction to Pandas Commands for Data Analysis

This repository contains basic commands in pandas for data analysis. The Jupyter notebook in this repository demonstrates how to read a dataset and initially explore the data using basic pandas functions like `head` and `tail`.

## Detailed Explanations and Examples

### Reading a Dataset

To read a dataset, we use the `read_csv` function from pandas. Here is an example:

```python
import pandas as pd

# Read the dataset
df = pd.read_csv('Salaries.csv')
```

### Exploring the Data

Once the dataset is loaded, we can explore it using various pandas functions. Here are some examples:

#### Displaying the First Few Rows

To display the first few rows of the dataset, we use the `head` function:

```python
# Display the first 5 rows
print(df.head())
```

#### Displaying the Last Few Rows

To display the last few rows of the dataset, we use the `tail` function:

```python
# Display the last 5 rows
print(df.tail())
```

## Dataset Description

The dataset used for data analysis in this repository is `Salaries.csv`. It contains information about the salaries of professors, including their rank, discipline, years since PhD, years of service, sex, and salary.
