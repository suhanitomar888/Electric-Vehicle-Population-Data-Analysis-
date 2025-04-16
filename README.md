# Electric-Vehicle-Population-Data-Analysis-
⚡ Electric Vehicle Population Data Analysis (Washington State)
This project performs an in-depth Exploratory Data Analysis (EDA) on Electric Vehicle (EV) registration data from Washington State. The goal is to identify trends, detect outliers, visualize adoption patterns, and gain insights into the future of sustainable transportation.

📁 Dataset Overview
Dataset: Electric_Vehicle_Population_Data.csv

Source: Washington State Department of Licensing (DOL)

Format: CSV

Records: ~150,000 rows

Key Features:

Model Year

Make & Model

EV Type (BEV, PHEV)

Electric Range

Base MSRP

County, City

Utility Provider

Clean Fuel Eligibility

🔧 Tools & Technologies Used
Python (Jupyter Notebook)

pandas, numpy

matplotlib, seaborn

🎯 Objectives
Clean and preprocess real-world EV registration data

Analyze EV distribution by city, county, and manufacturer

Visualize key metrics like EV type, model year, and range

Detect and illustrate outliers using the IQR method

Uncover trends using correlation analysis and quarterly growth

📊 Key Analyses & Visualizations
✔️ Data Cleaning:

Replaced missing values in numerical fields

Handled null strings and standardized text

Converted date fields and extracted quarter information

✔️ Outlier Detection:

Used Interquartile Range (IQR) to find anomalies in:

Fatality & Injury Count

Electric Range

Admin Division Population

Base MSRP

✔️ Visual Exploration:

Top 10 countries/cities by EV count (Bar Chart)

Fatalities vs Injuries (Scatter Plot)

Rainfall-triggered vs Other Landslides (Pie Chart)

Quarterly EV trend (Line Graph)

Correlation heatmap of numeric features

Pair plots and box plots for outlier analysis

🔍 Insights
King and Snohomish counties show the highest EV adoption.

Most EVs are recent model years (2018+), showing rapid growth.

BEVs (Battery Electric Vehicles) are more popular than PHEVs.

Higher electric range correlates with newer models.

Luxury brands (e.g., Tesla) dominate outliers in MSRP and range.

▶️ How to Run
Clone or download the repository

Open the notebook in JupyterLab or VSCode

Install dependencies (if not already installed):

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn
Run the notebook cells in order to reproduce the analysis

🔮 Future Scope
Add interactive dashboards using Plotly or Streamlit

Build machine learning models to predict EV growth

Use clustering to segment cities based on EV adoption behavior

Visualize EV charging station coverage with GIS tools
