Pandas Data Analysis with Jupyter Notebook
📌 About

This project contains Pandas practice and data analysis performed using Jupyter Notebook.

🛠️ Tools Used

Python

Pandas

Jupyter Notebook

📊 Topics

DataFrame creation

Reading data

Data filtering

Sorting

GroupBy

Data cleaning

Pivot Tables

Sales analysis

🚀 How to Run

Install Anaconda.

Open Jupyter Notebook.

Open pandas.ipynb.

Run the cells using Shift + Enter.

💻 Import Pandas
import pandas as pd

📈 Example
df = pd.read_csv("sales_data.csv")
df.head()

Pivot Table
pd.pivot_table(
    df,
    values="Sales",
    index="Product",
    columns="Region",
    aggfunc="sum"
)

🎯 Objective

The objective of this project is to learn Pandas and perform basic data analysis in Jupyter Notebook.

👤 Author

Inam Ullah
