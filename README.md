📊 Exploratory Data Analysis of Global Tobacco Surveillance System (GHPSS)
📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the Global Tobacco Surveillance System – Global Health Professions Student Survey (GHPSS) dataset. The goal is to uncover regional, topic-wise, and temporal patterns in tobacco-related indicators and to assess the reliability of survey estimates using statistical and visual analysis.

🎯 Objectives

Explore the distribution of tobacco-related indicators across WHO regions

Identify regional and topic-wise disparities in tobacco prevalence and surveillance focus

Analyze relationships between indicator values, confidence limits, and sample size

Perform univariate, bivariate, and multivariate analysis using appropriate visualizations

Generate data-driven insights to support public health interpretation

📂 Dataset Information

Source: Global Tobacco Surveillance System (GHPSS)

Records: ~15,000

Key Features:

WHO Region

Country

Topic

Indicator

Year

Data Value (percentage)

Low Confidence Limit

High Confidence Limit

Sample Size

The dataset is clean with no missing values in key analytical columns, allowing direct exploratory analysis.

🛠 Tools & Technologies

Python

Pandas (data manipulation)

Matplotlib & Seaborn (visualization)

Google Colab

GitHub

🔍 Methodology
1️⃣ Data Understanding

Loaded and inspected dataset structure, size, and data types

Verified data completeness and numerical ranges

2️⃣ Univariate Analysis

Univariate analysis was used to understand the distribution and variability of individual variables.

Key techniques:

Histogram and KDE plots for data_value

Boxplots to detect spread and outliers

Bar charts to analyze categorical distributions such as WHO regions

Purpose:

Identify skewness, range, and imbalance

Understand overall data behavior before comparisons

3️⃣ Bivariate Analysis

Bivariate analysis examined relationships between two variables at a time.

Numerical vs Numerical

Scatter plots between sample_size and data_value

Used to assess reliability and variability

Categorical vs Numerical

Boxplots comparing tobacco indicator values across WHO regions

Categorical vs Categorical

Cross-tabulation between WHO Region and Topic

Used to analyze differences in surveillance focus

Important Note:
Categorical relationships were analyzed using cross-tabulation, ensuring correct statistical methodology.

4️⃣ Multivariate Analysis

Multivariate analysis explored interactions among three or more variables.

Techniques used:

Pairplot for numerical variables (data_value, confidence limits, sample size)

Correlation heatmap using only numerical variables

Region × Topic × Data Value heatmap using aggregated (mean) values

Line plots to analyze short-term trends (2005–2011)

Purpose:

Identify complex patterns

Confirm consistency and reliability of survey estimates

📈 Key Insights
🔹 Distribution Insights

Tobacco indicator values range from 0 to 100, showing high variability across regions and indicators.

Sample size distribution is right-skewed, indicating many estimates are based on smaller samples.

🔹 Regional Insights

Significant disparities exist across WHO regions in tobacco indicator values.

Some regions show consistently higher medians and wider variability.

🔹 Topic-wise Insights

Surveillance focus differs by region, with certain topics emphasized more heavily in specific regions.

Multivariate heatmaps clearly highlight region–topic intensity patterns.

🔹 Reliability Insights

Strong linear relationships between data values and confidence limits confirm internal consistency.

Sample size shows weak association with indicator values, indicating reliability varies independently of prevalence.

🔹 Temporal Insights

Data spans 2005–2011, making it suitable for short-term policy-period analysis rather than long-term forecasting.

📊 Visualizations Included

Histograms and boxplots for univariate analysis

Scatter plots and boxplots for bivariate analysis

Cross-tabulation tables for categorical relationships

Multivariate heatmaps and pairplots

Trend analysis using line charts

Each visualization was selected based on data type and analytical purpose, following best practices in exploratory analysis.

✅ Conclusion

This project demonstrates how structured exploratory data analysis and appropriate visualization techniques can uncover meaningful public health insights from large surveillance datasets. The analysis reveals strong regional and topic-wise disparities, highlights variability in data reliability, and supports evidence-based interpretation of global tobacco surveillance data.

🔮 Future Scope

Year-wise regional modeling

Integration with external tobacco policy outcome data

Advanced statistical testing and predictive modeling

👤 Author

MOHAMED HALITH 

Bachelor of Computer Applications (BCA)

Aspiring Data Analyst

