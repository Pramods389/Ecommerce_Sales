# E-Commerce Customer Sales Analysis

This project is an exploratory data analysis (EDA) on an e-commerce dataset consisting of 1,000 records. The dataset contains customer demographics and purchase behavior. The project was carried out using **Pandas**, **NumPy**, and **Matplotlib**.

## 🔍 Objective

To perform a comprehensive data cleaning and analysis pipeline and derive business insights such as:

* Sales performance by gender, age, state, and occupation
* Patterns in purchasing behavior
* Understanding customer demographics

## 📁 Dataset

The dataset used was manually generated with typical data issues such as:

* Missing values in `Gender`, `Orders`, etc.
* Inconsistent formatting (e.g., `Amount` in words)
* Unstructured text

### Columns in Cleaned Dataset:

* `Customer_ID`
* `Cust_name`
* `Age`
* `Gender`
* `State`
* `Occupation`
* `Orders`
* `Amount`
* `Product_Category` *(generated)*

## 🧹 Step 1: Data Cleaning

* Converted `Age` column to integers.
* Handled missing values:

  * Replaced missing `Gender` with `Not specified`.
  * Filled missing `Orders` with the column mean.
* Converted `Amount` from string to numeric.
* Generated `Product_Category` using `random.choice()` with `np.random.seed(42)` to ensure consistency.

## 📊 Step 2: Data Visualization

### ✅ Plots Created:

#### 1. Gender Distribution (Pie Chart)

* Shows the percentage of customers by gender

#### 2. Age Distribution (Histogram)

* Displays customer age groups and their frequency

#### 3. Sales by Gender (Bar Plot)

* Compares total sales between male, female, and undefined genders

#### 4. Top 3 Revenue Generating States

* Bar chart of states with highest sales

#### 5. Top 3 Revenue Generating Occupations (Horizontal Bar Chart)

* Visualizes which occupations contribute more to revenue

#### 6. Age vs Purchase Amount (Scatter Plot)

* Shows correlation between customer age and amount spent

#### 7. TOP 5 Product Category by Sales(Bar Plot)

* Compares total sales between all the available Product Categories and extract the TOP 5.

## 📦 Libraries Used

* **Pandas** – data manipulation and cleaning
* **NumPy** – random value generation, numerical operations
* **Matplotlib** – all charts and plots

## 📌 Key Insights

* Female gender group spent more than others.
* Customers in states like Karnataka, Maharashtra and Tamil Nadu dominate the revenue.
* Customers within age groups 35-40 contribute to the sales in major way.
* Customers who are working in fields like Engineering tend to spend more.

## ✍️ Author

**Pramod S**
