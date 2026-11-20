# 🛍️ Customer Shopping Behavior Analysis

An end-to-end data analytics project focused on exploring customer shopping behavior using **Python, SQL (PostgreSQL), and Power BI**. The project demonstrates how raw shopping data can be transformed into meaningful insights to support data-driven business decisions.

## 📌 Project Overview

Understanding customer purchasing patterns helps businesses improve customer experience, identify trends, and make better business decisions.

In this project, I use Python for data exploration and preprocessing, PostgreSQL for storing and managing the processed data, and Power BI for data visualization and reporting.

## 🎯 Project Objectives

- Explore and understand customer shopping data.
- Perform data cleaning and preprocessing.
- Analyze customer purchasing behavior and trends.
- Store the processed dataset in a PostgreSQL database.
- Connect PostgreSQL with Power BI for reporting and visualization.
- Develop insights that can support business decisions.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Jupyter Notebook | Writing and executing Python code |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| PostgreSQL | Database management and storage |
| SQL | Querying and analyzing data |
| Power BI | Data visualization and dashboard development |

## 📂 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── README.md
└── .ipynb_checkpoints/
```

## ⚙️ Project Workflow

### 1. Data Loading and Exploration
- Import the dataset using Python.
- Examine the dataset structure and data types.
- Explore records and identify potential data quality issues.

### 2. Data Cleaning and Preprocessing
- Check for missing values.
- Identify duplicate records.
- Prepare the dataset for further analysis.

### 3. PostgreSQL Database Integration
- Create a PostgreSQL database.
- Establish a connection between Python and PostgreSQL.
- Store the processed DataFrame in a database table.
- Verify the stored records using SQL queries.

### 4. Power BI Integration
- Connect Power BI Desktop to PostgreSQL.
- Import the processed customer data.
- Create visualizations to explore shopping patterns.
- Present findings through an interactive dashboard.

## 💻 Installation and Setup

### Prerequisites
- Python 3.x
- Jupyter Notebook
- PostgreSQL
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/himanshuraj650/Customer-Shopping-Behavior-Analysis.git
```

```bash
cd Customer-Shopping-Behavior-Analysis
```

### Step 2: Install Python Libraries

```bash
pip install pandas numpy sqlalchemy psycopg2-binary jupyter
```

### Step 3: Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `Customer_Shopping_Behavior_Analysis.ipynb` and execute the cells in order.

### Step 4: Configure PostgreSQL

Create a database named `customer_analysis` in PostgreSQL and update the database connection details in the notebook with your own credentials.

**Important:** Never upload your actual database password or other private credentials to GitHub.

### Step 5: Connect Power BI

1. Open Power BI Desktop.
2. Select **Get Data → PostgreSQL database**.
3. Enter the server: `localhost:5432`.
4. Enter the database: `customer_analysis`.
5. Select the `public.customer` table.
6. Load the data and start building visualizations.

## 📊 Expected Outcomes

- Better understanding of customer shopping patterns.
- A structured and queryable PostgreSQL dataset.
- An interactive Power BI dashboard.
- Practical experience with an end-to-end data analytics workflow.

## 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Python Programming
- SQL and PostgreSQL
- Database Connectivity
- Data Visualization
- Business Intelligence

## 👨‍💻 Author

**Himanshu Raj**

B.Tech Computer Science and Engineering

GitHub: [@himanshuraj650](https://github.com/himanshuraj650)

Project Repository: [Customer Shopping Behavior Analysis](https://github.com/himanshuraj650/Customer-Shopping-Behavior-Analysis)

---

⭐ If you find this project useful, consider giving the repository a star!
