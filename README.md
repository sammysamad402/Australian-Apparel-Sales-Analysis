# 📊 Australian Apparel Sales Analysis & Business Intelligence Dashboard

## 👨‍💻 Author

**Abdul Samad Shaikh**
Bachelor of Engineering (Information Technology)

---

## 📌 Project Overview

This project presents a comprehensive sales analysis of **Australian Apparel Limited (AAL)**, a leading clothing company operating across multiple states in Australia. The company serves various customer segments including **Kids, Women, Men, and Seniors** and aims to expand its business through data-driven decision making.

The primary objective of this project is to analyze the company's fourth-quarter sales data and identify valuable business insights that can assist management in strategic planning, revenue optimization, and market expansion.

This project follows the complete Data Science workflow:

* Data Collection
* Data Wrangling
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization
* Business Intelligence Reporting
* Recommendations for Decision Making

---

## 🎯 Problem Statement

The CEO of Australian Apparel Limited tasked the Sales & Marketing department with identifying:

1. States generating the highest revenue.
2. States generating the lowest revenue.
3. Customer groups contributing the most and least sales.
4. Sales patterns across different periods.
5. Opportunities to improve sales performance in underperforming regions.

The analysis helps management make informed investment and marketing decisions for future business growth.

---

## 📂 Dataset Information

**Dataset Name:** AusApparalSales4thQrt2020.csv

The dataset contains fourth-quarter sales information for Australian Apparel Limited across multiple states and customer groups.

### Key Attributes

* Date
* State
* Group
* Unit
* Sales
* Time (if available)

---

## 🛠️ Technologies Used

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Programming Language      |
| Pandas           | Data Manipulation         |
| NumPy            | Numerical Computation     |
| Matplotlib       | Data Visualization        |
| Seaborn          | Statistical Visualization |
| SciPy            | Statistical Analysis      |
| Scikit-Learn     | Data Normalization        |
| Jupyter Notebook | Report Generation         |

---

## 📈 Project Workflow

### 1. Data Wrangling

The dataset was cleaned and inspected to ensure data quality.

Activities performed:

* Missing value detection using `isna()`
* Validation using `notna()`
* Duplicate record identification
* Data quality verification
* Data normalization using Min-Max Scaling

### Why Normalization?

Normalization converts numerical values to a common scale between 0 and 1, improving:

* Comparability
* Visualization quality
* Statistical analysis accuracy

---

### 2. Descriptive Statistical Analysis

Statistical measures were calculated for:

#### Sales

* Mean
* Median
* Mode
* Standard Deviation

#### Units Sold

* Mean
* Median
* Mode
* Standard Deviation

These metrics provide insights into central tendency and data variability.

---

### 3. Group-wise Sales Analysis

Sales performance was evaluated across customer categories:

* Kids
* Women
* Men
* Seniors

Objectives:

* Identify highest revenue-generating group
* Identify lowest revenue-generating group
* Understand customer purchasing behavior

---

### 4. State-wise Sales Analysis

Sales performance was analyzed across Australian states.

Objectives:

* Determine top-performing states
* Identify underperforming states
* Support future investment decisions

---

### 5. Time-Series Analysis

Reports were generated for:

* Weekly Sales
* Monthly Sales
* Quarterly Sales

Trend analysis helps management understand business performance over time.

---

## 📊 Data Visualization

Several visualizations were created to support business intelligence reporting.

### Visualizations Included

#### 📌 Box Plot

Used for:

* Outlier Detection
* Distribution Analysis
* Variability Assessment

#### 📌 State-wise Sales Bar Charts

Shows sales performance across different states.

#### 📌 Group-wise Sales Charts

Compares customer segments based on total revenue.

#### 📌 State vs Group Dashboard

Provides a combined view of:

* Customer groups
* Geographic performance

#### 📌 Sales Trend Charts

Weekly and monthly sales trends.

#### 📌 Distribution Plot

Created using Seaborn to visualize sales distribution and density.

---

## 🔍 Key Business Insights

The analysis identifies:

* Highest performing state
* Lowest performing state
* Most profitable customer group
* Least profitable customer group
* Sales trends over time
* Potential growth opportunities

These insights help management allocate resources more effectively.

---

## 💡 Business Recommendations

Based on the analysis, the following recommendations are proposed:

### 1. Increase Investment in High-Performing States

States generating the highest revenue should receive:

* Additional inventory
* Expanded operations
* Premium product launches

### 2. Improve Performance in Low-Revenue States

Implement:

* Regional marketing campaigns
* Discount programs
* Customer engagement initiatives

### 3. Target Low-Performing Customer Segments

Develop personalized promotions and loyalty programs to increase engagement.

### 4. Data-Driven Marketing

Use customer and regional insights to create targeted advertising campaigns.

### 5. Monitor Sales Trends Regularly

Continuous monitoring helps management quickly identify changing market conditions and customer behavior.

---

## 📁 Project Structure

```text
Australian-Apparel-Sales-Analysis/
│
├── Complete_AAL_Sales_Analysis_Notebook.ipynb
├── AusApparalSales4thQrt2020.csv
├── README.md
├── requirements.txt
├── LICENSE
│
└── images/
    ├── state_sales.png
    ├── group_sales.png
    ├── monthly_sales.png
    └── dashboard.png
```

---

## ▶️ How to Run the Project

### Clone Repository

```bash
git clone https://github.com/sammysamad402/Australian-Apparel-Sales-Analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
AAL_Sales_Analysis_Notebook.ipynb
```

Run all cells sequentially.

---

## 📚 Learning Outcomes

Through this project, the following concepts were applied:

* Data Cleaning
* Data Wrangling
* Statistical Analysis
* Exploratory Data Analysis (EDA)
* Business Intelligence Reporting
* Data Visualization
* Python for Data Science
* Decision Support Systems

---

## 🎓 Academic Information

**Student:** Abdul Samad Shaikh
**Degree:** Bachelor of Engineering (Information Technology)
**Project Type:** Applied Data Science with Python – IITG Course End Project

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Acknowledgement

This project was developed as part of academic learning in Data Science and Analytics to demonstrate practical application of Python-based data analysis techniques for real-world business decision making.
