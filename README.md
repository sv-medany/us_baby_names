# US - Baby Names Dataset Analysis

This project involves the analysis of a subset of the US Baby Names dataset from Kaggle, containing names from 2004 to 2014. The dataset provides information about baby names, genders, and the number of occurrences.

## Project Overview

This repository contains Python code for analyzing the US Baby Names dataset using the Pandas library. The analysis includes steps to import the dataset, clean the data, and derive various statistics related to baby names and their occurrences. The primary goals of this project are:

- Import the dataset from a provided address.
- Clean the data by filling missing values.
- Delete unnecessary columns ('Unnamed: 0' and 'Id').
- Determine whether there are more male or female names in the dataset.
- Group the dataset by name.
- Count the number of different names in the dataset.
- Identify the name with the most occurrences.
- Calculate the number of different names with the least occurrences.
- Calculate the median name occurrence.
- Calculate the standard deviation of name occurrences.
- Generate a summary statistics report with mean, min, max, std, and quartiles.

## Analysis Steps

1. Import the necessary libraries, including Pandas and NumPy.
2. Import the dataset from the provided address and fill missing values with zeros.
3. Delete the columns 'Unnamed: 0' and 'Id' from the dataset.
4. Determine whether there are more male or female names by grouping and counting occurrences.
5. Group the dataset by name and assign it to the variable 'names'.
6. Calculate the number of different names in the dataset using the 'ngroups' attribute.
7. Identify the name with the most occurrences by calculating the sum and finding the index with 'idxmax()'.
8. Calculate the number of different names with the least occurrences by filtering the groups and calculating shape.
9. Calculate the median name occurrence by calculating the median of the sum of occurrences.
10. Calculate the standard deviation of name occurrences using the 'std()' function.
11. Generate a summary statistics report with mean, min, max, std, and quartiles using the 'describe()' function.

## Repository Structure

```
US-Baby-Names-Analysis/
│
├── baby_names_analysis.ipynb  # Jupyter Notebook containing analysis code
└── readme.md                  # Project overview and details
```

## Usage

1. Clone the repository using: `git clone https://github.com/your-username/US-Baby-Names-Analysis.git`
2. Navigate to the repository: `cd US-Baby-Names-Analysis`
3. Open the `baby_names_analysis.ipynb` notebook to access the detailed analysis steps and results.

## Acknowledgments

- Special thanks to Kaggle for providing the US Baby Names dataset for analysis.
- Appreciation to the creators and contributors of the Pandas and NumPy libraries for empowering data analysis.

---
