📊 Sports Data Analysis – Week 1 Project
📌 Overview

This project focuses on data cleaning and preprocessing of a sports dataset using Python.
The dataset contains player performance metrics such as goals, assists, distance covered, and match results.

The goal of this project is to transform messy, inconsistent data into a clean and structured format for further analysis.

📂 Dataset Information
The dataset includes the following columns:
player_id
Player Name
team
match_date
sprints
top_speed(km/h)
distance_km
goals
assists
minutes_played
result

⚙️ Technologies Used
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
Plotly

🧹 Data Cleaning Steps
1. Handling Missing Values
Filled missing player names with "Unknown"
Filled missing team names with "Unknown Team"
Replaced missing dates with a default value
2. Data Type Conversion
Converted columns like sprints, top_speed, distance_km to numeric
Handled invalid entries like "twenty", "NaN", etc.
3. Cleaning Text Data
Standardized match results:
Win, Loss, Draw
Fixed inconsistent values in minutes_played (e.g., "eighty" → 80)
4. Date Formatting
Converted multiple date formats into a standard datetime format

📈 Key Features
Handles messy real-world data
Converts mixed data types into usable formats
Prepares dataset for visualization and analysis
Uses reusable cleaning functions

🚀 How to Run
Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
Install required libraries:
pip install pandas numpy matplotlib seaborn plotly
Run the Jupyter Notebook:
jupyter notebook

📊 Output
Cleaned dataset ready for analysis
Standardized and structured data
Improved data quality for insights

🎯 Learning Outcomes
Data cleaning techniques
Handling missing and inconsistent data
Working with real-world datasets
Using Pandas for preprocessing

📌 Future Improvements
Add data visualization dashboards
Perform exploratory data analysis (EDA)
Build predictive models

👤 Author
NANDANI SUTHAR
