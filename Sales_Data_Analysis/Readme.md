\# Sales Data Analysis \& Dashboard



\## 📊 Project Overview



This project focuses on analyzing sales data to understand business performance through \*\*Python, Excel, and Power BI\*\*.



The analysis covers sales, profit, quantity sold, discounts, product performance, regional performance, and time-based trends.



\---



\## 📁 Project Structure



```text

Sales-Data-Analysis/

│

├── README.md

│

├── Dataset/

│   └── cleaned\_dataset.csv
    └── Sales\_dataset.csv
│

├── Python\_EDA/

│   └── Sales\_EDA.ipynb

│

├── Excel\_Analysis/

│   └── Sales\_Analysis.xlsx

│

└── PowerBI\_Dashboard/

&#x20;   └── Sales\_Dashboard.pbix



📌 Dataset



The dataset contains 1,000 sales transactions with the following columns:



Column		Description

Date		Date of the transaction

Region		Region where the sale occurred

Product		Product sold

Quantity	Number of units sold

Sales		Revenue generated

Discount	Discount applied

Profit		Profit generated



🐍 Python EDA



Python was used to perform Exploratory Data Analysis (EDA).



* Analysis Performed
* Dataset inspection
* Data types analysis
* Missing value analysis
* Duplicate analysis
* Descriptive statistics
* Sales analysis
* Profit analysis
* Product-wise analysis
* Region-wise analysis
* Quantity analysis
* Discount analysis
* Time-based analysis
* Data visualization



Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn



The complete Python analysis is available in:



Python\_EDA/Sales\_EDA.ipynb



📗 Excel Analysis



Excel was used for additional business analysis.



* Analysis Performed
* Monthly Sales
* Yearly Sales
* Sales by Product
* Sales by Region
* Profit by Product
* Discount by Product



The Excel analysis is available in:



Excel\_Analysis/Sales\_Analysis.xlsx



📊 Power BI Dashboard



An interactive Power BI dashboard was created to visualize the sales data.



Dashboard Pages

1\. Sales Overview



Includes:



* Total Sales
* Total Profit
* Total Quantity
* Profit Margin
* Total Transactions
* Average Discount
* Monthly Sales Trend
* Profit by Month
* Quantity Sold by Month
* Average Discount by Month



Interactive slicers:



* Date
* Product
* Region



2\. Product Analysis



Includes:



* Sales by Product
* Profit by Product
* Quantity Sold by Product
* Discount by Product



3\. Regional Analysis



Includes:



* Sales by Region
* Profit by Region
* Quantity by Region
* Average Discount by Region



The Power BI dashboard is available in:



PowerBI\_Dashboard/Sales\_Dashboard.pbix



📈 Key Metrics



The Power BI dashboard includes the following measures:



DAX



Total Sales = SUM('cleaned\_dataset'\[Sales])



Total Profit = SUM('cleaned\_dataset'\[Profit])



Total Quantity = SUM('cleaned\_dataset'\[Quantity])



Average Discount = AVERAGE('cleaned\_dataset'\[Discount])



Profit Margin = DIVIDE(\[Total Profit], \[Total Sales], 0)



Total Transactions = COUNTROWS('cleaned\_dataset')



🛠️ Tools \& Technologies



* Python – Exploratory Data Analysis
* Pandas – Data manipulation
* NumPy – Numerical analysis
* Matplotlib – Visualization
* Seaborn – Visualization
* Microsoft Excel – Data analysis
* Power BI – Dashboard development
* GitHub – Project management and version control



🎯 Project Objectives



* Analyze sales performance
* Understand profit trends
* Compare product performance
* Compare regional performance
* Analyze quantity and discount patterns
* Perform Exploratory Data Analysis using Python
* Perform business analysis using Excel
* Build an interactive Power BI dashboard
* Present data-driven insights through visualizations



📂 Project Deliverables



* Cleaned sales dataset
* Python EDA notebook
* Excel analysis workbook
* Power BI dashboard



🚀 How to Use



Python



Open Sales\_EDA.ipynb in Google Colab or Jupyter Notebook and run the analysis.



Excel



Open Sales\_Analysis.xlsx to explore the Excel-based analysis.



Power BI



Open Sales\_Dashboard.pbix using Power BI Desktop to interact with the dashboard.



👩‍💻 Author



Srilakshmi



A practical data analytics project demonstrating skills in:



* Data Analysis
* Exploratory Data Analysis
* Data Visualization
* Excel
* Power BI
* Python
* Business Intelligence



