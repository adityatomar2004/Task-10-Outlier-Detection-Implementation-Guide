# Python EDA & Outlier Detection (Task 10)

## 📋 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** and implementing **Outlier Detection** techniques using Python. It demonstrates the ability to clean raw datasets, visualize distributions, and handle statistical anomalies using the Interquartile Range (IQR) method.

## 📊 Dataset Information
* [cite_start]**Name:** Student Performance (student-por.csv) [cite: 10]
* **Description:** This dataset contains student performance data including demographic details and academic scores.

## 🛠️ Workflow Implemented
[cite_start]Following the task guidelines[cite: 12], the analysis was conducted through the following steps:
1. [cite_start]**Initial Inspection:** Used `.shape`, `.info()`, and `.head()` to understand data types and structure[cite: 13].
2. [cite_start]**Descriptive Statistics:** Generated summary statistics using `.describe()` to identify the mean, median, and spread[cite: 14].
3. [cite_start]**Missing Value Analysis:** Computed the percentage of missing values for each column to ensure data quality[cite: 15].
4. [cite_start]**Visual Distribution:** Created histograms to see data spread and boxplots to visually identify outliers[cite: 16].
5. [cite_start]**Outlier Detection (IQR Method):** [cite: 17, 29]
    * Calculated Q1 (25th percentile) and Q3 (75th percentile).
    * Defined boundaries using $IQR = Q3 - Q1$.
    * [cite_start]Flagged and handled outliers (capping/removal) based on statistical reasoning[cite: 18, 19].
[Image of IQR method boxplot]
6. [cite_start]**Correlation Analysis:** Developed a correlation matrix to interpret top relationships between variables[cite: 20].

## 🧰 Tools & Libraries
* [cite_start]**Environment:** Google Colab [cite: 5]
* [cite_start]**Primary Libraries:** `pandas`, `numpy`, `matplotlib` [cite: 6]

## 📁 Repository Structure
* [cite_start]`task10_eda.ipynb`: The complete Python notebook containing analysis and visualizations[cite: 22].
* [cite_start]`cleaned_dataset.csv`: The final processed dataset after cleaning and outlier handling[cite: 23].
* [cite_start]`eda_findings.txt`: A summary of key insights derived from the EDA process.
* `student-por.csv`: The raw dataset used for the analysis.

---

### How to Use
1. Clone this repository to your local machine.
2. Ensure you have `pandas`, `numpy`, and `matplotlib` installed.
3. Open the `.ipynb` file in Google Colab or Jupyter Notebook to view the full execution and findings.
