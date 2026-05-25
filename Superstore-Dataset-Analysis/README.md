📌 Project Overview
This project performs a complete Exploratory Data Analysis (EDA) on the popular Superstore Sales Dataset from Kaggle. The goal is to uncover business insights related to sales performance, profitability, regional trends, and customer behavior using Python.

📊 Dataset Information
FeatureDetailSourceKaggle - Superstore DatasetRows9,994Columns21Time Period2014 – 2017
Key Columns:

Sales — Revenue from each order
Profit — Profit/loss from each order
Discount — Discount applied
Category / Sub-Category — Product type
Region — US region (West, East, Central, South)
Segment — Customer type (Consumer, Corporate, Home Office)


🧹 Data Cleaning

✅ Removed duplicate records
✅ Handled missing values (median for numeric, mode for categorical)
✅ Converted date columns to proper datetime format
✅ Standardized numeric columns
✅ Result: 0 missing values after cleaning


📈 Exploratory Data Analysis (EDA)
1️⃣ Sales Distribution

Sales is right-skewed — most orders are low value
Few orders contribute very high revenue

2️⃣ Profit by Sub-Category
Top Profitable ✅Top Loss-Making ❌CopiersTablesPhonesBookcasesAccessoriesMachines
3️⃣ Sales by Region
RegionPerformanceWest🥇 Highest SalesEast🥈 GoodCentral🥉 ModerateSouth⚠️ Lowest
4️⃣ Customer Segment

Consumer → Most orders (5,191)
Corporate → Moderate (3,020)
Home Office → Lowest (1,783)

5️⃣ Category Performance

Technology → Most profitable ✅
Office Supplies → High sales, moderate profit
Furniture → Good sales but often negative profit ❌

6️⃣ Monthly Sales Trend

Sales peak heavily in October – December (holiday season)
Summer months show lower activity


💡 Key Insights & Recommendations
✅ Business Strengths

Technology category performing very strongly
West region contributes most revenue
Consumer segment is the biggest buyer

⚠️ Areas to Improve

Furniture (especially Tables) → generating huge losses
Discount strategy needs optimization
South & Central regions need better marketing

📋 Recommendations

Reduce discounting on loss-making categories
Increase focus on high-profit items (Copiers, Phones)
Improve marketing in low-performing regions
Analyze supplier costs for Furniture to reduce losses


🛠️ Tech Stack
ToolPurposePythonCore programmingPandasData manipulationNumPyNumerical operationsMatplotlibData visualizationSeabornStatistical plotsGoogle ColabDevelopment environment

📂 Project Structure
Superstore-Analysis/
├── superstore_analysis.ipynb   # Main analysis notebook
├── Sample - Superstore.csv     # Dataset
└── README.md                   # Project documentation

🚀 How to Run
bash# Clone the repo
git clone https://github.com/samichohan/Data-Analysis-Projects.git

# Open the notebook
jupyter notebook superstore_analysis.ipynb
Or open directly in Google Colab.

👤 Author
Sami Chohan
