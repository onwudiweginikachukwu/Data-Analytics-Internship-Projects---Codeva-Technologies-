# Data-Analytics-Internship-Projects---Codveda-Technologies-
Welcome to my Data Analytics Internship Portfolio. This repository showcases the projects I completed during my internship at Codeva Technologies, where I gained hands-on experience in data cleaning, exploratory data analysis, machine learning, and dashboard development using Python and Power BI.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Power BI Desktop
- Git & GitHub

 # 📁 LEVEL 1

# 🔹 Task 1: Data Cleaning

## 🎯 Objective

Clean and preprocess the stock prices dataset by identifying and handling missing values, duplicates, and incorrect data types to prepare the data for analysis.



## 📂 Dataset

Stock Prices Dataset



## 🛠️ Tools Used

- Python
- Pandas



## ⚙️ Methodology

- Imported the dataset using Pandas.
- Checked for missing values.
- Checked for duplicate records.
- Verified the data types.
- Cleaned the dataset and prepared it for further analysis.



## 📊 Results

- The dataset was successfully cleaned.
- Missing values and duplicate records were handled.
- The dataset became suitable for Exploratory Data Analysis and Machine Learning.

![](https://github.com/onwudiweginikachukwu/Data-Analytics-Internship-Projects---Codeva-Technologies-/blob/main/Task%201.PNG)

## 💡 Key Insight

Proper data cleaning improves the quality of analysis and ensures reliable machine learning results.



# 🔹 Task 2: Exploratory Data Analysis (EDA)

## 🎯 Objective

Explore the stock prices dataset to identify trends, distributions, and relationships among numerical variables.



## 📂 Dataset

Stock Prices Dataset



## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib



## ⚙️ Methodology

- Calculated summary statistics.
- Generated histograms.
- Generated box plots.
- Generated scatter plots.
- Generated a correlation heatmap.



## 📊 Results

- Open, High, Low, and Close prices showed a very strong positive correlation.
- Trading Volume showed a weak negative correlation with stock prices.
- Several outliers were detected in Trading Volume.



## 💡 Key Insight

Stock prices tend to move together, while trading volume varies independently and contains more extreme values.



# 📷 Project Outputs

## Correlation Heatmap

![](https://github.com/onwudiweginikachukwu/Data-Analytics-Internship-Projects---Codeva-Technologies-/blob/main/Heatmap%20image.png)



## Histogram

![](https://github.com/onwudiweginikachukwu/Data-Analytics-Internship-Projects---Codeva-Technologies-/blob/main/Histogram%20image.png)



## Scatter Plot

![](https://github.com/onwudiweginikachukwu/Data-Analytics-Internship-Projects---Codeva-Technologies-/blob/main/Scatter%20plot%20image.png)



## Box Plot

![](https://github.com/onwudiweginikachukwu/Data-Analytics-Internship-Projects---Codeva-Technologies-/blob/main/Boxplot%20image.png)


# 📁 LEVEL 2

# 🔹 Task 1: Regression Analysis

## 🎯 Objective

Build and evaluate a Linear Regression model to predict stock closing prices.


## 📂 Dataset

Stock Prices Dataset



## 🛠️ Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib



## ⚙️ Methodology

- Split the dataset into training and testing sets.
- Trained a Linear Regression model.
- Evaluated the model using Mean Squared Error (MSE) and R² Score.



## 📊 Results

- MSE: 2.643850081593318
- R2 Score: 0.9997449719375414
- Coefficient: [0.99994654]
- Intercept: 0.02258065463259129

![](https://github.com/onwudiweginikachukwu/Data-Analytics-Internship-Projects---Codeva-Technologies-/blob/main/Regression%20output%20snap.png)


## 💡 Key Insight

The model achieved excellent predictive performance, explaining approximately *99.9%* of the variation in stock closing prices.



# 🔹 Task 2: K-Means Clustering

## 🎯 Objective

Group similar observations using the K-Means clustering algorithm.



## 📂 Dataset

Iris Dataset



## 🛠️ Tools Used

- Python
- Scikit-learn
- Matplotlib



## ⚙️ Methodology

- Standardized the dataset.
- Applied the Elbow Method.
- Trained the K-Means clustering model.
- Visualized the resulting clusters.



## 📊 Results

The Iris dataset was successfully grouped into 3 clusters based on feature similarities.



## 💡 Key Insight

K-Means clustering effectively grouped similar observations, demonstrating how unsupervised learning can reveal hidden patterns in data.



## 📷 Elbow Method

![](https://github.com/onwudiweginikachukwu/Data-Analytics-Internship-Projects---Codeva-Technologies-/blob/main/Elbow_method_graph.png)



## 📷 Cluster Visualization

![](https://github.com/onwudiweginikachukwu/Data-Analytics-Internship-Projects---Codeva-Technologies-/blob/main/Cluster%20Visualization.png)


# 📁 LEVEL 3

# 🔹 Task 1: Predictive Modeling (Classification)

## 🎯 Objective

Build and evaluate machine learning models to predict customer churn based on customer usage patterns and service information.



## 📂 Dataset

Churn BigML Dataset

- Training Dataset: churn-bigml-80.csv
- Testing Dataset: churn-bigml-20.csv



## 🛠️ Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib



## ⚙️ Methodology

- Loaded the training and testing datasets.
- Performed data preprocessing and feature selection.
- Trained a classification model.
- Evaluated the model using Accuracy, Precision, Recall and F1 Score.
- Improved the model using hyperparameter tuning.



## 📊 Results

| Metric | Value |
|---------|--------|
| Accuracy | *85%* |
| Precision | *51%* |
| Recall | *25%* |
| F1 Score | *33%* |


## 💡 Key Insight

The model achieved good overall accuracy in predicting customer churn. However, the lower Recall and F1 Score indicate that there is room for improvement in identifying customers who are likely to churn.



# 📷 Classification Output

![](https://github.com/onwudiweginikachukwu/Data-Analytics-Internship-Projects---Codeva-Technologies-/blob/main/Predictive%20snap.png)



# 🔹 Task 2: Interactive Power BI Dashboard

## 🎯 Objective

Develop an interactive dashboard using Power BI to visualize stock market performance and enable users to explore trends through interactive filters and visualizations.



## 📂 Dataset

Stock Prices Dataset



## 🛠️ Tools Used

- Power BI Desktop



## ⚙️ Dashboard Features

- KPI Cards
- Line Chart
- Column Chart
- Slicers (Date and Symbol)
- Interactive Filters



## 📊 Dashboard Insights

- Average Closing Price: *86.37*
- Highest Closing Price: *2049.00*
- Lowest Closing Price: *1.59*
- Total Trading Volume: *2 Trillion*



## 💡 Key Insight

The dashboard allows users to interactively analyze stock prices and trading volume by filtering the data using stock symbols and dates. It provides a clear overview of stock performance through dynamic visualizations.



# 📷 Dashboard Preview

![](https://github.com/onwudiweginikachukwu/Data-Analytics-Internship-Projects---Codeva-Technologies-/blob/main/Stock%20Dashboard.png)




# 🚀 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Linear Regression
- K-Means Clustering
- Classification Modeling
- Hyperparameter Tuning
- Data Visualization
- Dashboard Development
- Power BI
- Python Programming
- Machine Learning



# 🙏 Acknowledgement

These projects were completed as part of the *Data Analytics Internship at Codveda Technologies*. The internship provided practical experience in data cleaning, exploratory data analysis, machine learning, predictive modeling, clustering, and dashboard development using Python and Power BI.



## ⭐ Thank You

Thank you for taking the time to explore this repository. Feedback and suggestions are always welcome.

## 📬 Connect With Me

If you'd like to connect or view more of my work, feel free to reach out.

![LinkedIn](https://www.linkedin.com/in/onwudiwe-ginikachukwu-7426a233a)
![GitHub](https://github.com/onwudiweginikachukwu)

⭐ If you found this repository helpful, consider giving it a star.
 
