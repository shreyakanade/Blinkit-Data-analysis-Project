🚀 Blinkit Sales Analysis – Data Analytics Project

A comprehensive data analysis project on Blinkit Sales Dataset to identify key revenue drivers, customer behavior patterns, product performance, and actionable business insights.
This project uses Python, Pandas, NumPy, Matplotlib, Seaborn, and Power BI/Tableau for end-to-end analysis and visualization.

📌 Project Overview

Blinkit (formerly Grofers) is a quick-commerce platform dealing with groceries and daily essentials.
This analysis aims to:

Understand overall sales performance

Identify top-performing categories

Analyze outlet-level performance

Explore the impact of item visibility, fat content, price, and location type on sales

Provide data-driven business recommendations

🗂️ Dataset Description

The dataset includes the following key columns:

Feature	Description
Item_Identifier	Unique product ID
Item_Weight	Weight of the item
Item_Fat_Content	Fat content (Regular / Low Fat)
Item_Visibility	Shelf visibility
Item_Type	Category
Item_MRP	Price
Outlet_Identifier	Outlet ID
Outlet_Establishment_Year	Establishment year
Outlet_Size	Small / Medium / High
Outlet_Location_Type	Tier of location
Outlet_Type	Supermarket / Grocery
Sales	Total sales of the item
🧹 Data Cleaning & Preprocessing

✔ Handled missing values (Item Weight, Outlet Size)
✔ Corrected inconsistent categorical values (e.g., Low Fat, LF, low fat → Low Fat)
✔ Removed trailing spaces in column names
✔ Handled outliers using IQR
✔ Created new features such as:

Outlet Age

Sales per Visibility

📊 Exploratory Data Analysis (EDA)

Key insights from the analysis:

🔹 1. Sales Distribution

Most products fall within a moderate MRP range.

High-priced items contribute more revenue.

🔹 2. Item Fat Content vs Sales

Regular items generate higher sales than Low Fat items.

🔹 3. Outlet Location Type

Tier 3 outlets show the highest sales, followed by Tier 2 and Tier 1.

🔹 4. Item Type Analysis

Fruits & Vegetables, Snack Foods, and Household items are top revenue categories.

🔹 5. Item Visibility Impact

Low visibility items surprisingly have higher sales → indicating strong customer demand.

📈 Visualizations

The analysis includes multiple charts:

Bar plot: Sales by Item Type

Heatmap: Correlation between numeric features

Line chart: Outlet age vs sales

Bar chart: Fat content vs sales

Pie chart: Outlet Type distribution

Grouped bar chart: Outlet Location Type vs Fat Content Sales

🧠 Business Insights & Recommendations
✔ Improve inventory levels for high-demand categories

(Fruits, Snacks, Household)

✔ Increase visibility for high-performing but low-visibility items

→ Improve shelf placement & app promotions.

✔ Focus more on Tier-3 outlets

→ They deliver the highest revenue.

✔ Offer combo discounts on Regular-Fat items

→ They drive maximum sales.

✔ Optimize pricing for high-MRP items

→ These have strong impact on total revenue.

🛠️ Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook / Google Colab

Power BI 

Excel

Git & GitHub

📁 Project Structure
Blinkit-Sales-Analysis/
│── data/
│   └── blinkit_data.xlsx
│── notebooks/
│   └── blinkit_sales_analysis.ipynb
│── images/
│   └── charts and visualizations
│── README.md
└── requirements.txt

How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/your-username/Blinkit-Sales-Analysis.git
cd Blinkit-Sales-Analysis

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run Jupyter Notebook
jupyter notebook

4️⃣ Open the project notebook
blinkit_sales_analysis.ipynb

🎯 Conclusion

This project provides deep insights into Blinkit's sales behavior using data analysis and visualization techniques. It can be used for:

Business decision-making

Portfolio/resume showcase

Interview demonstrations

Understanding real-world retail analytics
