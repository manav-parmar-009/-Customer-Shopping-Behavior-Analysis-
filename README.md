# 🛍️ Customer Shopping Behavior Analysis

### Turning Customer Data into Meaningful Business Insights

An exploratory data analysis project focused on understanding customer purchasing behavior, shopping patterns, customer segmentation, regional performance, and marketing experiment outcomes using Python.

---

## 📌 Project Overview

Understanding customer behavior is essential for businesses to improve customer experience, optimize marketing strategies, and increase sales.

This project explores **10,000 customer activity records** to identify patterns in customer demographics, loyalty tiers, purchasing decisions, traffic sources, and promotional experiments.

Using Python, Pandas, NumPy, and Matplotlib, I performed data inspection, data quality checks, exploratory data analysis (EDA), and data visualization to extract meaningful insights from the dataset.

The primary objective is to understand:

- Who are the customers?
- Which loyalty tiers generate higher spending?
- Which regions contribute the most purchases?
- Which traffic sources attract customers?
- How do promotional experiments influence purchasing behavior?
- What patterns can be identified in customer shopping activity?

---

## 🎯 Project Objectives

- Understand customer demographics and purchasing behavior.
- Analyze customer distribution across loyalty tiers.
- Compare spending patterns across different customer segments.
- Evaluate regional and traffic-source performance.
- Analyze purchasing behavior across promotional experiment groups.
- Identify trends through statistical analysis and visualization.
- Convert raw customer data into actionable business insights.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Jupyter Notebook | Interactive analysis environment |

---

## 📂 Dataset Information

The dataset contains **10,000 records and 20 columns** representing customer demographics, shopping activity, purchasing behavior, and promotional experiments.

| Attribute | Details |
|---|---|
| Total Records | 10,000 |
| Total Columns | 20 |
| Unique Customers | 9,938 |
| Missing Values | 0 |
| Duplicate Records | 0 |
| File Format | CSV |

### Dataset Features

| Category | Columns |
|---|---|
| Customer Information | customer_id, age, income_k |
| Time Information | week |
| Customer Segmentation | loyalty_tier, region |
| Shopping Behavior | prior_3mo_visits, prior_3mo_spend |
| Website Activity | session_duration_sec, pages_viewed, cart_adds |
| Purchase Information | purchased, order_value, returned |
| Marketing | traffic_source, experiment_group |
| Promotional Details | discount_applied, shipping_cost |
| Customer Experience | satisfaction_score |
| Device Information | device |

---

## 🔍 Project Workflow

The project follows a structured data analysis workflow:

**1. Data Loading**
- Imported the dataset using Pandas.
- Inspected the first, last, and random records.
- Checked dataset dimensions and column names.

**2. Data Understanding**
- Examined column data types.
- Used descriptive statistics to understand numerical distributions.
- Identified important customer and shopping attributes.

**3. Data Quality Assessment**
- Checked missing values across all columns.
- Identified duplicate records.
- Examined unique customer IDs.
- Verified data types.

**4. Exploratory Data Analysis**
- Customer demographics analysis.
- Loyalty tier analysis.
- Regional performance analysis.
- Traffic source analysis.
- Promotional experiment comparison.
- Purchasing behavior analysis.

**5. Data Visualization**
- Bar charts
- Histograms
- Box plots
- Pie charts
- Line charts

---

## 📊 Key Analysis & Findings

### 1. Customer Demographics

Analyzed customer age and income distribution.

- Average customer age: **37.38 years**
- Youngest customer: **18 years**
- Oldest customer: **80 years**
- Average income: **68.75K**

### 2. Customer Loyalty Analysis

Compared customer distribution, satisfaction, income, and previous spending across loyalty tiers.

| Loyalty Tier | Customers | Average Previous 3-Month Spending |
|---|---:|---:|
| Bronze | 4,527 | 111.45 |
| Silver | 2,966 | 141.49 |
| Gold | 1,782 | 175.23 |
| Platinum | 712 | 222.79 |

**Key Insight:** Platinum customers have the highest average previous three-month spending, while Bronze customers represent the largest customer segment.

### 3. Regional Analysis

Compared customer distribution, purchases, income, and spending across four regions.

| Region | Customers | Purchases |
|---|---:|---:|
| South | 3,460 | 467 |
| Midwest | 2,266 | 284 |
| West | 2,131 | 297 |
| Northeast | 2,128 | 300 |

**Key Insight:** The South region has the highest number of customers and recorded purchases among the four regions.

### 4. Traffic Source Analysis

Evaluated customer acquisition channels and their associated spending and order values.

| Traffic Source | Customers |
|---|---:|
| Organic | 3,466 |
| Paid Search | 2,529 |
| Social | 1,794 |
| Email | 1,705 |
| Affiliate | 494 |

**Key Insight:** Organic traffic contributes the largest customer count, while Email has the highest average order value among the traffic sources.

### 5. Promotional Experiment Analysis

Compared three experiment groups:

- Control
- Discount10
- FreeShip

| Experiment Group | Customers | Purchase Rate |
|---|---:|---:|
| Control | 3,950 | 12.76% |
| Discount10 | 3,512 | 14.42% |
| FreeShip | 2,522 | 13.31% |

**Key Insight:** Discount10 recorded the highest purchase rate among the three experiment groups.

This is an observed difference and does not independently establish statistical significance or causation.

---

## 📈 Visualizations

The project includes visual analysis of:

- Customer distribution by loyalty tier.
- Customer age distribution.
- Customer income distribution.
- Income distribution using a box plot.
- Customer distribution by experiment group.
- Weekly purchase trends.

These visualizations help identify patterns and communicate findings more effectively.

---

## 💡 Business Insights

The analysis provides several useful business observations:

1. **Customer Segmentation:** Higher loyalty tiers are associated with higher average previous spending.

2. **Regional Performance:** The South region contributes the largest customer base and purchase count.

3. **Marketing Channels:** Organic traffic is the largest source of customers.

4. **Customer Acquisition:** Email traffic has the highest average order value in the analyzed dataset.

5. **Promotional Strategies:** Discount10 recorded the highest observed purchase rate, making it an interesting candidate for further experimentation.

6. **Customer Experience:** Average customer satisfaction is approximately 3.72 out of 5.

---

## 🚀 How to Run This Project

### Prerequisites

Make sure Python is installed on your system.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/customer-shopping-behavior-analysis.git
```

### 2. Navigate to the Project Directory

```bash
cd customer-shopping-behavior-analysis
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Analysis

Open the Jupyter Notebook and execute the cells sequentially.

Make sure `data.csv` is placed in the same directory as the notebook.

---

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data.csv
├── python.ipynb
└── README.md
```

---

## 📚 What I Learned

Through this project, I strengthened my practical understanding of:

- Data cleaning and data quality assessment.
- DataFrame operations using Pandas.
- GroupBy operations and aggregation.
- Descriptive statistical analysis.
- Customer segmentation.
- Exploratory Data Analysis (EDA).
- Data visualization using Matplotlib.
- Extracting business insights from raw datasets.

---

## 🔮 Future Improvements

Some areas I would like to explore further:

- Build an interactive dashboard using Power BI.
- Perform deeper statistical analysis of promotional experiments.
- Explore customer segmentation techniques.
- Analyze customer conversion and retention patterns.
- Develop predictive models for purchase behavior.

---

## 👨‍💻 Author

**Manav Parmar**

B.Tech – Computer Science and Engineering (AI, ML, DS)

Interested in Python, Data Analytics, Artificial Intelligence, and solving real-world problems through data.

📌 GitHub: [Manav Parmar](https://github.com/manav-parmar-
