# Customer Segmentation Using Unsupervised Learning

## 📌 Project Overview

This project focuses on customer segmentation using **unsupervised machine learning**.

The goal is to analyse customer information such as income, spending, family size, age, education and purchasing behaviour, and divide customers into groups with similar characteristics.

The project uses **Python, Pandas, Seaborn, PCA, K-Means Clustering and Agglomerative Clustering**.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand customer characteristics and purchasing behaviour.
- Clean and prepare the customer dataset.
- Create useful features from the existing data.
- Identify unusual values and remove outliers.
- Convert categorical data into numerical values.
- Scale the data for machine learning.
- Reduce the number of features using PCA.
- Find a suitable number of customer clusters using the Elbow Method.
- Segment customers into different groups using clustering.
- Visualise and compare the customer clusters.

---

## 📊 Dataset

The project uses a customer marketing campaign dataset.

The dataset contains information about:

- Customer income
- Age
- Education
- Family size
- Number of children
- Customer registration date
- Product spending
- Deals purchased
- Accepted marketing campaigns
- Complaints
- Other customer characteristics

---

## 🛠️ Technologies and Tools

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

### Machine Learning Techniques

- Feature Engineering
- Label Encoding
- Standard Scaling
- Principal Component Analysis (PCA)
- K-Means Clustering
- Agglomerative Clustering
- Elbow Method

---

## 🔄 Project Workflow

The project follows these main steps:

### 1. Data Loading

The customer marketing dataset is loaded into a Pandas DataFrame.

### 2. Data Cleaning

The dataset is checked for:

- Missing values
- Incorrect data types
- Unusual values
- Unnecessary columns

### 3. Feature Engineering

New features are created to make the customer information more useful.

Examples include:

- `Age`
- `Spent`
- `Customer_For`
- `Children`
- `Family_Size`
- `Is_Parent`
- `Living_With`

### 4. Outlier Removal

Extreme values in **Age** and **Income** are removed to reduce their effect on the clustering analysis.

### 5. Encoding Categorical Data

Categorical features such as education and living situation are converted into numerical values using **Label Encoding**.

### 6. Feature Scaling

The features are standardised using `StandardScaler`.

This puts the variables on a similar scale before clustering.

### 7. PCA

**Principal Component Analysis (PCA)** is used to reduce the dataset to three main components.

This makes the data easier to analyse and visualise.

### 8. Elbow Method

The Elbow Method is used to determine a suitable number of clusters.

The analysis identifies **4 clusters** for the K-Means clustering step.

### 9. Customer Clustering

Customers are grouped using:

- K-Means Clustering
- Agglomerative Clustering

### 10. Cluster Analysis

The clusters are visualised and compared using:

- Income
- Spending
- Number of deals purchased
- Accepted promotions
- Age
- Family size
- Other personal characteristics

---

## 📈 Visualisations

The project includes several visualisations, including:

- Feature pair plots
- PCA 3D projection
- Elbow Method
- Income vs Spending scatter plot
- Spending distribution by cluster
- Promotion acceptance by cluster
- Deals purchased by cluster
- Personal characteristics vs spending

These visualisations help understand the differences between customer groups.

---

## 📁 Project Structure

```text
customer-segmentation-kmeans-clustering/
│
├── Customer_Segmentation.ipynb
├── marketing_campaign.csv
├── README.md
└── requirements.txt# UnsupervisedLearning_CustomerSegmentation_DataAnalysis_Project
Customer segmentation using Python, Pandas, Seaborn, PCA, and K-Means clustering to analyse customer spending, income, demographics, and purchasing behaviour.
