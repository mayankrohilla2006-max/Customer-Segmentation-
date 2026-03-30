# Customer Segmentation using K-Means Clustering 🎯

## Overview
This repository contains a complete machine learning pipeline for **Customer Segmentation** using **K-Means Clustering**. The project aims to analyze a customer dataset, engineer relevant features, and group customers into distinct segments based on their demographics and purchasing behavior. This allows businesses to understand their customer base better and tailor targeted marketing strategies.

## Project Workflow
1. **Data Preprocessing & Cleaning:** Handling missing values (e.g., median imputation for income) and removing irrelevant identifiers.
2. **Feature Engineering:** - Calculating customer `Age` from birth year.
   - Aggregating total spend across product categories (`Total_Spent`).
   - Combining household metrics (`Total_Children`).
   - Calculating customer loyalty/tenure in days.
3. **Data Transformation:** Encoding categorical variables using `LabelEncoder` and scaling numerical features using `StandardScaler` to optimize distance calculations.
4. **Optimal Cluster Selection:** Using the **Elbow Method** to determine the optimal number of clusters (K).
5. **K-Means Clustering:** Assigning customers to distinct behavioral groups.
6. **Dimensionality Reduction (PCA):** Applying Principal Component Analysis to visualize high-dimensional customer segments on a 2D plot.
7. **Cluster Profiling:** Generating business profiles for each segment (e.g., average income, spend, and age per cluster).

## Tech Stack 🛠️
* **Language:** Python 3.x
* **Libraries used:** * `pandas` & `numpy` (Data Manipulation)
  * `matplotlib` & `seaborn` (Data Visualization)
  * `scikit-learn` (Machine Learning: K-Means, PCA, Preprocessing)

## Installation & Setup 💻
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/customer-segmentation.git](https://github.com/your-username/customer-segmentation.git)
   cd customer-segmentationwn
# Customer Segmentation using K-Means Clustering 🎯

## Overview
This repository contains a complete machine learning pipeline for **Customer Segmentation** using **K-Means Clustering**. The project aims to analyze a customer dataset, engineer relevant features, and group customers into distinct segments based on their demographics and purchasing behavior. This allows businesses to understand their customer base better and tailor targeted marketing strategies.

## Project Workflow
1. **Data Preprocessing & Cleaning:** Handling missing values (e.g., median imputation for income) and removing irrelevant identifiers.
2. **Feature Engineering:** - Calculating customer `Age` from birth year.
   - Aggregating total spend across product categories (`Total_Spent`).
   - Combining household metrics (`Total_Children`).
   - Calculating customer loyalty/tenure in days.
3. **Data Transformation:** Encoding categorical variables using `LabelEncoder` and scaling numerical features using `StandardScaler` to optimize distance calculations.
4. **Optimal Cluster Selection:** Using the **Elbow Method** to determine the optimal number of clusters (K).
5. **K-Means Clustering:** Assigning customers to distinct behavioral groups.
6. **Dimensionality Reduction (PCA):** Applying Principal Component Analysis to visualize high-dimensional customer segments on a 2D plot.
7. **Cluster Profiling:** Generating business profiles for each segment (e.g., average income, spend, and age per cluster).

## Tech Stack 🛠️
* **Language:** Python 3.x
* **Libraries used:** * `pandas` & `numpy` (Data Manipulation)
  * `matplotlib` & `seaborn` (Data Visualization)
  * `scikit-learn` (Machine Learning: K-Means, PCA, Preprocessing)

