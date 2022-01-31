# UCI Adult Dataset Exploratory Data Analysis

The purpose of this report is to identify meaningful insights from the UCI-Adult Dataset by performing an exploratory data analysis on it. The workflow is the same as traditional data analytics, which includes obtaining, cleaning, analyzing, splitting data, and using the K-means Clustering algorithm for modelling.

## UCI - Adult Dataset Description

The UCI-Adult Dataset inculcates various factors that affect the annual income of an individual. It is influenced by an individual's age, education level, gender, occupation, etc. The Adult dataset is widely cited for the K-nearest Clustering Algorithm and is quite famous for data pre-processing and machine learning practices. The dataset contains 14 feature columns and one target column: the 'salary' divided into two classes of salary above 50K and below 50K. "Extracted by Barry Becker from the 1994 Census database. A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1) && (HRSWK>0))" (UCI Machine Learning Repository, Dataset Description).

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following packages.

```bash
pip install import numpy
pip install import matplotlib
pip install import seaborn
```

## Obtaining Data

The UCI-Adult Dataset is available on the UCI-Machine Learning repository. The dataset is available in '.data' format and can be readily accessed using notepad and Microsoft Excel. Read the dataset using Panda's 'read_csv' method. However, using Excel's text import wizard, the '.data' file was converted to a '.csv' file and uploaded to google drive for shared access. To mount the data in the python notebook 'mount' method was used with the 'read_csv' method to create a data frame with the name 'MyDataFrame' for the dataset UCI_Adult_Dataset.csv.' Following is the link to the dataset but there is a CSV file in the repository as well.

[Dataset Link](https://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.data)

## Usage

Run the 'Final Code.ipynb' file.
