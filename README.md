# 📚 Student Performance Analysis – EDA & Power BI Dashboard

## 📌 Project Overview

This project involves performing **Exploratory Data Analysis (EDA)** on a real-world student performance dataset to uncover patterns related to exam scores and demographic factors. The main goal is to identify the key drivers of student success and create an interactive **Power BI Dashboard** that visualizes meaningful insights.

Python is used for data cleaning, analysis, and feature engineering, while Power BI is used for dynamic, user-friendly visualization of trends and comparisons.

---

## 📁 Dataset Information

- **Source**: [Kaggle – Student Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Records**: 1,000
- **Features**:
  - `gender`: male or female
  - `race/ethnicity`: group A, B, C, D, or E
  - `parental level of education`: highest education level of parents
  - `lunch`: standard or free/reduced
  - `test preparation course`: completed or none
  - `math score`, `reading score`, `writing score`: scores out of 100

---

## 🎯 Project Goals

- Clean and preprocess the dataset using Python
- Add calculated columns: total score, average score, performance category
- Explore patterns using univariate and multivariate EDA
- Answer tricky business questions (e.g., gender performance, test prep impact)
- Build a Power BI dashboard with slicers and rich visuals

---

## 🔍 Exploratory Data Analysis (EDA)

### 🧼 Data Cleaning & Feature Engineering:
- Checked for null values and data types
- Added:
  - `total_score`: Sum of all three subject scores
  - `average_score`: Mean of scores
  - `performance_category`: Based on average score (Low, Medium, High)

### 📊 Analysis Performed:

#### Parental Education:
- Which parental level leads to higher scores

#### Gender Comparison:
- Performance comparison in math, reading, and writing

#### Test Preparation:
- Impact of completing the test prep course on all subjects

#### Group & Demographic Insights:
- Top 10% scorer profiles (gender + lunch + test prep)
- Lunch impact across different ethnic groups
- Score correlation matrix

#### Performance Segmentation:
- Created Low/Medium/High performers using Pandas logic

---

## 📊 Power BI Dashboard

The dashboard provides an interactive way to filter and view insights using **slicers**, **KPI cards**, and **visual charts**.

### Dashboard Pages & Visuals:

#### 1. Overview
- KPI Cards: Average Math, Reading, Writing Scores
- Slicers: Gender, Lunch, Test Preparation

#### 2. Insights by Demographics
- Bar Chart: Avg scores by parental education
- Clustered Column: Test prep vs non-prep comparison
- Donut Chart: Distribution of performance categories

#### 3. Distribution & Trends
- Box Plot (via custom visual or workaround): Subject scores by gender
- Matrix Heatmap: Lunch impact across race/ethnicity

---

## 🛠️ Tools & Technologies

- **Python**: pandas, numpy, seaborn, matplotlib
- **Jupyter Notebook**: for writing and running EDA code
- **Power BI Desktop**: for building dashboards
- **CSV**: for transferring data between Python and Power BI

---

## 📁 Project Structure

```

StudentPerformanceAnalysis\_Project3\_HafsaNoor/
├── Cleaned\_StudentPerformance.csv          # Cleaned dataset with engineered columns
├── HafsaNoor\_StudentPerformanceAnalysis\_Project3.ipynb  # EDA notebook
├── PowerBI\_Dashboard\_HafsaNoor.pbix        # Power BI dashboard file
├── README.md                                # Project documentation

````

---

## 💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/HafsaNoorMuhammad26/Student-Performance-Analysis-EDA.git
cd StudentPerformanceAnalysis_Project3
````

### 2. Run the EDA notebook

Open the `HafsaNoorMuhammad_StudentPerformanceAnalysis_Project3.ipynb` file in Jupyter Notebook or Google Colab to explore the code and insights.

### 3. Open the Power BI Dashboard

Launch `HafsaNoorMuhammad_PowerBI_Dashboard_StudentPerformanceAnalysis_Project3.pbix` in Power BI Desktop and use slicers to explore demographic filters and performance trends.

---

## 📌 Key Takeaways

* Demographic and environmental factors (like parental education and lunch type) can influence student performance
* Test preparation programs significantly boost average scores
* Visualizing data using Power BI enables interactive and more insightful exploration
* Simple logic in Pandas can help categorize students into performance bands

---

## 🙋‍♀️ Author

**Hafsa Noor Muhammad**
🎓 Final Year Software Engineering Student, UIT University
 
Feel free to reach out via 
🔗 [LinkedIn](https://www.linkedin.com/in/hafsa-noor-muhammad-67b96331a/) 
                    OR 
🔗 [GitHub](https://github.com/HafsaNoorMuhammad26)
---

⭐ *If you found this project helpful, don’t forget to star the repo and share with your peers!*
