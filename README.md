# PandasOverviewCommands <!-- omit in toc -->

## Contents <!-- omit in toc -->

- [1. Installation](#1-pandas-installation)
  - [1.1 How install](#11-how-install)
  - [1.2 How Import](#12-how-import)
- [2. Explorating data-methods-attributes](#2-explorating-data-methods-attributes)
- [3. Indexing and selection](#3-indexing-and-selection)
- [4. Data cleaning](#4-data-cleaning)
- [5. Data manipulation](#5-data-manipulation)


## 1. Installation

### 1.1. How install
Install Pandas: You can install Pandas using pip or conda in your command prompt or terminal:
- pip install pandas
- conda install pandas

### 1.2 How import
Import Pandas: To use Pandas in your Python script, you first need to import it:
- import pandas as pd
- The pd alias is commonly used to refer to Pandas.

## 2. Explorating data-methods-attributes
- Load Data: You can load data into a Pandas DataFrame using various methods, such as read_csv(), read_excel(), read_sql(), etc. Here's an example using read_csv():
df = pd.read_csv('data.csv')
- This will load the data from the data.csv file into a Pandas DataFrame called df.
- Exploring Data: You can explore the data in your DataFrame using various methods and attributes. Some useful ones are: df.head()      # to display the first few rows of data
df.tail()      # to display the last few rows of data
df.info()      # to display information about the DataFrame
df.describe()  # to display summary statistics for the DataFrame



