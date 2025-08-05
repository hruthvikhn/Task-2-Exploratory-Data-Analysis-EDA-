# Task 2: Exploratory Data Analysis using Airlines Dataset

Hey there! 
This repository contains my work for **Task 2** of the AI & ML Internship, where I explored an airline flights dataset using various data visualization and statistical tools.

The main goal of this task is to understand the data better — by spotting patterns, trends, and anomalies.


## What I Did

Here’s a quick breakdown of everything I explored:

### 1. Summary Statistics
- Calculated mean, median, standard deviation, etc.
- Got a feel for distributions, ranges, and skews.

### 2. Handled Missing Values
- Every column had 1 missing value (as seen in `.isnull()`).
- I filled:
  - Numeric columns (`duration`, `days_left`, `price`) with mean/median.
  - Categorical columns (`airline`, `class`, etc.) with the most frequent value.

### 3. Visualized the Data
- Created **histograms** to check value distributions.
- Used **boxplots** to find outliers.
- Built a **correlation heatmap** to identify feature relationships.
- Created **pairplots** to visualize how numerical features interact.
- Compared **categorical features with price** using grouped boxplots.

### 4. Observations & Insights
- Business class tickets are clearly more expensive than economy.
- Flights with more stops generally cost less.
- Booking earlier (more `days_left`) often leads to lower prices.
- Some features are slightly skewed or have outliers that may affect modeling.



## Tools Used

- **Google Colab** for notebook execution
- **Pandas** & **NumPy** for data wrangling
- **Seaborn** & **Matplotlib** for plotting
- **Standard Python libraries** for stats and logic



## Files in This Repo

- `Task_2_Hruthvik_H_N.ipynb` → My Colab notebook
- `README.md` → This File


Thanks for reading! Feel free to explore the notebook and reach out if you have feedback or suggestions.
