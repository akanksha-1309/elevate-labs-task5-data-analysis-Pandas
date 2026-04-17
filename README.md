# 📊 Task 5 – Data Analysis on CSV Files using Pandas

## 📌 Objective
To analyze sales data using Python Pandas and generate meaningful insights using data aggregation and visualization techniques.

---

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook / VS Code (Jupyter Extension)

---

## 📂 Dataset Information
A sample sales dataset was created containing the following columns:

- Date
- Product
- Region
- Sales
- Quantity
- Profit

The dataset was saved as a CSV file and loaded using Pandas for analysis.

---

## 📊 Steps Performed

### 1. Data Creation
A sample dataset was created manually and converted into a DataFrame.

### 2. CSV Handling
The dataset was saved as a CSV file and reloaded using `pandas.read_csv()`.

### 3. Data Exploration
- Used `df.head()`
- Used `df.info()`
- Used `df.describe()`
- Checked missing values using `df.isnull().sum()`

### 4. Data Analysis
Performed grouping operations:
- Total Sales by Product
- Total Sales by Region
- Total Profit by Product

### 5. Data Visualization
Created charts using Matplotlib:
- Bar chart → Sales by Product
- Pie chart → Sales by Region
- Line chart → Sales Trend

---

## 📈 Key Insights
- Laptop generated the highest total sales
- North region contributed the most revenue
- Sales distribution varies across products
- Data visualization helps in better business understanding

---

## 📁 Project Structure
```
Task5_Data_Analysis/
│
├── task5.ipynb
├── sales_data.csv
├── README.md
└── screenshots/
```

---

## 📸 Output Screenshots
Screenshots are included in the `screenshots/` folder showing:
- Data preview
- Groupby results
- Bar chart
- Pie chart
- Line chart

---

## 👨‍💻 Author
Akanksha Jadhav

---

## 🚀 Conclusion
This project demonstrates basic Exploratory Data Analysis (EDA) using Python Pandas, including data cleaning, grouping, and visualization for extracting business insights.