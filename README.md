# House Sales Prediction - King County, USA

In this project, I analyzed **house sales data** from **King County, USA**, which includes Seattle and surrounding areas.  
The goal of the project was to **predict house prices** based on various features such as the number of bedrooms, bathrooms, square footage, grade, and other property attributes.

Using Python, I performed **data preprocessing, exploratory data analysis (EDA), feature engineering**, and built **machine learning models** to predict housing prices accurately.

---

## **Dataset Information**

The dataset contains **house sale prices** for King County, USA, between **May 2014 and May 2015**.  
It was slightly modified for the purpose of this course.

| **Variable**       | **Description** |
|---------------------|------------------|
| id                 | A unique identifier for the house |
| date               | Date when the house was sold |
| price              | **Target variable** → Sale price of the house |
| bedrooms           | Number of bedrooms |
| bathrooms          | Number of bathrooms |
| sqft_living        | Square footage of the living space |
| sqft_lot           | Square footage of the lot |
| floors             | Total number of floors |
| waterfront         | 1 if the house has a waterfront view, else 0 |
| view               | Number of times the house has been viewed |
| condition          | Overall condition of the house |
| grade              | Grade given based on King County grading system |
| sqft_above         | Square footage of the house apart from the basement |
| sqft_basement      | Square footage of the basement |
| yr_built           | Year the house was built |
| yr_renovated       | Year the house was renovated |
| zipcode            | Zip code of the house |
| lat                | Latitude coordinate |
| long               | Longitude coordinate |
| sqft_living15      | Living room area in 2015 (post-renovations) |
| sqft_lot15         | Lot size in 2015 (post-renovations) |

---

## **Objectives**

After completing this project, I was able to:

- Load and clean **real-world housing data**.
- Perform **data preprocessing**: handling missing values, outliers, and feature scaling.
- Conduct **exploratory data analysis (EDA)** to identify patterns and correlations.
- Build **machine learning models** for predicting house prices.
- Evaluate models using performance metrics such as **R² score**, **MSE**, and **RMSE**.

---

## **Project Overview**

The project focuses on applying **data analysis** and **machine learning techniques** to predict house prices:

### **Key Steps**
1. **Importing Libraries**  
   Using NumPy, Pandas, Matplotlib, Seaborn, and Scikit-Learn.
   
2. **Loading and Understanding the Dataset**  
   Read the dataset and explored its structure, size, and statistical details.

3. **Data Preprocessing**  
   - Handling missing values.
   - Encoding categorical variables.
   - Normalizing and scaling numerical features.
   - Checking for outliers.

4. **Exploratory Data Analysis (EDA)**  
   - Analyzing price distribution.
   - Visualizing correlations using heatmaps and pair plots.
   - Understanding the effect of features like bedrooms, bathrooms, and location on price.

5. **Model Building**  
   - **Linear Regression**
   - **Ridge Regression**
   - **Lasso Regression**
   - **Decision Trees / Random Forests**

6. **Model Evaluation**  
   Evaluated models using:
   - R² Score
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)

7. **Predictions**  
   Used the trained models to predict house prices for unseen data.

---

## **Technologies Used**
- Python 3
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook

---


matplotlib
seaborn
