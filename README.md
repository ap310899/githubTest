# githubTest
**1.  Project Title:**


Data Analysis with Pandas: Exploring and Visualizing Salary Dataset

**2.  Short Description:**

Explore the Salary dataset to find insights! This set of 78 records provides an overview of salaries, service years, ranks, disciplines, and level of education. Explore the data, use Python and Pandas to identify trends and visualize patterns. An ideal environment for improving the skills you have in data analysis.

**3.  Getting Started:**


**Introduction:**

Welcome to the "Data Analysis with Pandas" project! This project focuses on exploring and visualizing a salary dataset using Python and the Pandas library.

**4.  Prerequisites:**


Before get started, ensure that we have the following prerequisites installed on our system:

I. Python install

II. Pandas library install

**5.  Installing:**

**Install dependencies:**

pip install pandas

**6.  Running the Tests:**

**In [1]:** 

#Import Python Libraries

import pandas as pd

**In [2]:**

#Read csv file

df = pd.read_csv("C:/Users/LENOVO/Documents/DATA 1202 - Data Analysis Tools for Analytics/Salaries.csv")

**In [3]:**

#Find how many records this data frame has

df.shape

**Out [3]:**

(78, 6)

**In [4]:**

#How many elements are there?

df.size

**Out [4]:**

468

**In [5]:**

#What are the column names?

df.columns

**Out [5]:**

Index(['rank', 'discipline', 'phd', 'service', 'sex', 'salary'], dtype='object')

**In [6]:**

#What types of columns we have in this data frame?

df.dtypes

**Out [6]:**

rank          object

discipline    object

phd            int64

service        int64

sex           object

salary         int64

dtype: object

**In [7]:**

#Check a particular column type

df.phd.dtype

**Out [7]:**

dtype('int64') 

**7.  How to deploy on GitHub Pages:**

I. **Create a `docs` folder:** Place HTML, CSS, or other static files in a `docs` folder at the root of your repository.

II. **Enable GitHub Pages:** In your GitHub repository, go to Settings > Pages, and select the `main` branch and `/docs` folder.

III. **Access your deployed site:** Your analysis will be accessible at `https://your-username.github.io/your-repository`.
