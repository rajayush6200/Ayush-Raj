# Exploratory Data Analysis (EDA) Course Project – Phase 1 & Phase 2

## Student Information

- **Name:** Ayush Raj
- **Registration Number:** 23BDS0312
- **Course:** Exploratory Data Analysis (BCSE331L)
- **Dataset:** County Murders (`countymurders.csv`)
- **Institution:** VIT Vellore

---

# Course Project – Phase 1 & Phase 2

## Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on the **County Murders** dataset across two phases:

- **Phase 1** covers exploratory data analysis including data loading, cleaning, descriptive statistics, univariate analysis, outlier detection, and bivariate/multivariate analysis.
- **Phase 2** extends the analysis with 1-D statistical analysis, 2-D statistical analysis, 3-D statistical analysis, time series analysis, and unsupervised machine learning techniques (K-Means Clustering and Hierarchical Clustering).

---

## Dataset Information

- **Dataset Name:** County Murders
- **File:** `countymurders.csv`
- **Records:** 37,349
- **Original Features:** 21

The dataset contains demographic, crime, population, density, arrest, execution, and murder-related information for counties across the United States.

---

## Project Objectives

- Understand the dataset structure
- Perform data cleaning and preprocessing
- Generate descriptive statistics
- Conduct univariate analysis
- Perform bivariate and multivariate analysis
- Identify relationships between important variables
- Visualize insights using statistical plots
- Perform 1-D statistical analysis
- Perform 2-D statistical analysis
- Perform 3-D statistical analysis
- Conduct Time Series Analysis
- Apply K-Means Clustering
- Apply Hierarchical Clustering

---

## Project Structure

### Phase 1

#### 1. Data Loading
- Import required libraries
- Load dataset into Pandas DataFrame

#### 2. Basic Statistical Analysis
- Dataset information
- Missing value analysis
- Descriptive statistics
- Numerical and categorical feature identification

#### 3. Data Cleaning
- Missing value treatment
- Duplicate checking
- Data quality verification

#### 4. Univariate Analysis
- Histograms
- Box Plots
- Count Plots
- Distribution analysis

#### 5. Outlier Detection
- Box plot analysis
- Distribution comparison

#### 6. Correlation Analysis
- Correlation matrix
- Heatmap visualization

#### 7. Bivariate Analysis
- Scatter Plot
- Regression Plot
- Correlation Heatmap

#### 8. Multivariate Analysis
- Pair Plot
- Cluster Map
- Standardized Box Plot

#### 9. Conclusion
- Summary of findings
- Key insights

---

### Phase 2

#### 10. 1-D Statistical Analysis
- Measures of central tendency (mean, median, mode)
- Measures of dispersion (variance, standard deviation, range, IQR)
- Skewness and kurtosis
- Frequency distribution
- Histograms and KDE plots
- Box plots and violin plots

#### 11. Time Series Analysis
- Annual time-series aggregation
- Population-adjusted murder and arrest rates
- Time indexing
- Autocorrelation analysis
- Augmented Dickey-Fuller stationarity testing
- First differencing
- ARIMA model comparison and selection

#### 12. 2-D Statistical Analysis
- Covariance analysis
- Pearson correlation
- Scatter plots
- Regression plot
- Correlation heatmap
- Contingency tables
- Pair plot

#### 13. 3-D Statistical Analysis
- Three-variable statistical summaries
- Covariance and correlation
- 3-D scatter plots
- Standardized 3-D visualization
- Three-variable correlation heatmap

#### 14. K-Means Clustering
- Data preparation
- Standardization
- Elbow/inertia analysis
- Silhouette analysis
- Selection of cluster count based on silhouette score
- Cluster sizes and profiles
- 2-D and 3-D cluster visualizations
- Cluster profile heatmaps

#### 15. Hierarchical Clustering
- Representative sample selection
- Standardization
- Euclidean distance
- Ward's linkage method
- Dendrogram
- Three-cluster assignment
- Cluster sizes and percentages
- Cluster profiles
- Cluster visualizations and heatmaps

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

## Key Findings

- The dataset contains demographic and crime-related information for over **37,000 counties**.
- Population shows a strong positive relationship with the number of murders.
- Population density has only a weak positive relationship with murder rate.
- Several variables contain significant outliers.
- Correlation analysis highlights both strong and weak relationships among variables.
- Multivariate analysis provides deeper insights into interactions between important numerical features.
- Time series analysis reveals trends and stationarity properties in murder and arrest rates over time.
- K-Means and Hierarchical Clustering identify distinct county groupings based on crime and demographic characteristics.

---

## Repository Contents

```
Ayush-Raj/
│
├── EDA_Course_Project_Phase1.ipynb
├── countymurders.csv
└── README.md
```

---

## How to Run

1. Clone this repository

```bash
git clone https://github.com/rajayush6200/Ayush-Raj.git
```

2. Open the notebook using **Google Colab** or **Jupyter Notebook**

3. Install required libraries if needed

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

4. Run all notebook cells sequentially.

---

## Results

The notebook includes:

- Data preprocessing
- Statistical summaries
- Data visualization
- Relationship analysis
- Correlation analysis
- Multivariate analysis
- Phase 1 exploratory analysis
- 1-D statistical analysis
- 2-D statistical analysis
- 3-D statistical analysis
- Time Series Analysis
- K-Means Clustering
- Hierarchical Clustering
- Final conclusions

---

## Author

**Ayush Raj**

Registration Number: **23BDS0312**

Course: **Exploratory Data Analysis (BCSE331L)**

VIT Vellore

---

## License

This project is submitted as part of the **BCSE331L – Exploratory Data Analysis Course Project (Phase 1 & Phase 2)** for academic purposes.