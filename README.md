# 📦 Supply Chain Analysis using Python

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** and **Supply Chain Performance Analysis** using Python.

A global e-commerce company manages product fulfillment, shipping, and delivery across multiple regions. The business faces issues with **delivery delays**, **inconsistent shipping performance**, and **profitability variations**.

This analysis aims to identify:

- Delivery delay patterns
- Profitability impact of shipping delays
- Supply chain bottlenecks
- Root causes of late deliveries
- Time-based shipment trends

---

## 🎯 Business Problem

The company experiences situations where **actual delivery times differ from scheduled shipment times**, leading to:

- Customer dissatisfaction
- Increased operational costs
- Reduced profitability
- Supply chain inefficiencies

The goal is to analyze operational data and uncover actionable insights to improve supply chain performance.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** — Data Cleaning & Analysis
- **NumPy** — Numerical Operations
- **Matplotlib** — Data Visualization
- **Seaborn** — Statistical Visualizations
- **Jupyter Notebook**

---

## 📂 Datasets Used

This project uses **two datasets**:

### 1. DataCoSupplyChainDataset.csv
Main dataset containing real-world supply chain operational data.

Includes information related to:

- Orders
- Customers
- Products
- Sales & Profit
- Shipping Details
- Delivery Status
- Regions & Markets
- Order Dates
- Shipping Modes

### 2. DescriptionDataCoSupplyChain.csv
Supporting dataset containing **column descriptions and metadata** for the main dataset.

Used for:

- Understanding dataset attributes
- Feature interpretation
- Data dictionary/reference purposes

---

Source: **DataCo Global Supply Chain Dataset**
---

## 📊 Analysis Performed

### 1. Data Cleaning & Preprocessing

Performed operations such as:

- Handling missing values
- Removing unnecessary columns
- Duplicate checking
- Feature engineering

Created new features:

- **Order Processing Time**
- **Delay**
- **Is_Delayed Flag**
- **Order Month / Day / Hour**
- **Profitability Flag**

---

### 2. Exploratory Data Analysis (EDA)

Analyzed:

- Dataset structure
- Missing values
- Categorical distributions
- Profit vs Loss orders
- Delivery delay patterns

---

### 3. Profitability vs Delivery Analysis

Studied relationship between:

- Delivery delay days
- Average profit per order
- Total profit
- Order count

Goal:

Determine how shipping delays affect business profitability.

---

### 4. Bottleneck Detection

Identified supply chain bottlenecks by analyzing delayed delivery percentage across categories such as:

- Shipping Mode
- Customer Segment
- Department
- Order Status
- Product Categories

---

### 5. Root Cause Analysis

Performed regional analysis to identify major drivers behind late deliveries.

Examined factors including:

- Shipping Mode
- Customer Segment
- Department Name
- Order Type
- Order Status

---

### 6. Time-Based Analysis

Analyzed delay trends across:

- **Months**
- **Days of Week**
- **Hours of Day**

Used visualizations to detect seasonal and operational delay patterns.

---

## 📈 Visualizations

The project includes multiple charts such as:

- Pie Charts
- Bar Charts
- Line Plots
- Delay Distribution Graphs
- Profitability Analysis Charts
- Time Trend Visualizations

---

## 📌 Key Insights

Some major findings from the analysis:

✔ Delivery delays significantly influence profitability.

✔ Certain shipping methods and operational categories show higher late delivery percentages.

✔ Regional differences impact supply chain performance.

✔ Time-based patterns reveal periods with higher delivery risks.

---

## 🚀 Project Structure

```plaintext

Supply-Chain-Analysis/
│
├── Supply Chain Analysis.ipynb
├── DataCoSupplyChainDataset.csv
├── DescriptionDataCoSupplyChain.csv
├── README.md
```


---

## ▶️ How to Run

### 1. Clone Repository

```bash
git clone <your_repository_link>
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run Notebook

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```plaintext
Supply Chain Analysis.ipynb
```

---

## 📚 Learning Outcomes

Through this project, I learned:

- Real-world EDA workflow
- Supply Chain KPI analysis
- Feature engineering
- Data cleaning techniques
- Business problem solving with data
- Visualization and storytelling

---

## 👨‍💻 Author

**Toufique Khan**

B.Tech Computer Science Student  
Interested in **Data Analytics, Data Science, and Frontend Development**.
