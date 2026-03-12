📊 Sales Data Analysis with Pandas

This project performs Exploratory Data Analysis (EDA) on a large sales dataset using Python, Pandas, and Matplotlib.

The goal of the project is to clean raw sales data and extract useful business insights such as sales trends, customer purchasing behavior, and product performance.

This project demonstrates how data scientists use Pandas for real-world data analysis workflows.

🚀 Project Goals

The project answers several real business questions:

1️⃣ What was the best month for sales?
2️⃣ Which city generated the highest revenue?
3️⃣ What time should advertisements be displayed to maximize purchases?
4️⃣ Which products are most often bought together?
5️⃣ Which product sold the most and why?

🛠️ Tech Stack
Tool	Purpose
Python	Programming language
Pandas	Data cleaning & analysis
NumPy	Numerical operations
Matplotlib	Data visualization
Jupyter Notebook	Interactive analysis
📂 Project Structure
Data-Science-With-Pandas
│
├── Sales_Data/
│   ├── Sales_January_2019.csv
│   ├── Sales_February_2019.csv
│   ├── ...
│
├── Sales_Analysis.ipynb
│
└── README.md

The dataset contains monthly sales data for an electronics store in 2019.

🧹 Data Cleaning Process

Before analysis, the dataset was cleaned using Pandas:

Removed missing values

Removed duplicated header rows

Converted columns to correct data types

Extracted Month, City, and Hour features from order data

This step ensures accurate analysis and reliable insights.

📈 Key Insights
1️⃣ Best Month for Sales

Sales were aggregated by month to determine which month generated the highest revenue.

📌 This helps businesses understand seasonal demand patterns.

2️⃣ City with Highest Sales

Sales were grouped by city using Pandas groupby().

📌 This shows where the largest customer base exists.

3️⃣ Best Time to Advertise

Order timestamps were analyzed to determine peak purchasing hours.

📌 Businesses can schedule advertisements during these hours.

4️⃣ Products Bought Together

Orders with the same Order ID were analyzed to find product combinations frequently purchased together.

📌 Useful for product bundling and recommendation systems.

5️⃣ Most Sold Products

Product demand was analyzed by counting total quantities sold.

📌 Helps companies understand which products drive revenue.

📊 Example Visualizations

The project includes visualizations such as:

Monthly Sales Bar Chart

Orders by Hour Graph

Sales by City

Product Demand Analysis

These visualizations help convert raw data into meaningful insights.

▶️ How to Run the Project
1 Clone the repository
git clone https://github.com/Aryan1152002/Data-Science-With-Pandas.git
2 Navigate to the project directory
cd Data-Science-With-Pandas
3 Install required libraries
pip install pandas numpy matplotlib jupyter
4 Start Jupyter Notebook
jupyter notebook

Open Sales_Analysis.ipynb and run the cells.

🎯 Skills Demonstrated

This project demonstrates the following data science skills:

Data Cleaning

Feature Engineering

Exploratory Data Analysis

Pandas GroupBy Operations

Data Visualization

Extracting Business Insights from Data

👨‍💻 Author

Aryan Singh

GitHub
https://github.com/Aryan1152002

⭐ If you found this project helpful, consider starring the repository.
