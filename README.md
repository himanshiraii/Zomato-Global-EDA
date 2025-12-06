# 🔴 Zomato-Global-EDA
An end-to-end Exploratory Data Analysis (EDA) of global Zomato data. Project features dynamic filtering logic to identify Top/Least restaurants by City/Metric, supported by robust data cleaning that correctly analyzed zero-vote restaurants and preserved market-defining outliers. The findings are presented using Zomato-branded visuals

# 📌 Project Overview
The goal of this project is to:
Understand the structure and quality of the Zomato dataset
Perform data cleaning: handling duplicates, dropping irrelevant columns
Explore key business indicators such as:
Popular cuisines
Restaurant ratings
Cost for two distribution
City-wise restaurant distribution
Prepare a clean dataset suitable for future modeling and dashboarding.

# 🧰 Technologies Used
Python,
Pandas – data loading & preprocessing,
NumPy – numerical handling,
Matplotlib / Seaborn – visual analysis,
Jupyter Notebook – execution environment.

# 📂 Key Steps in the Notebook
1️⃣ Introduction to the Data
The project begins with loading the dataset (zomato.csv), inspecting its structure, reviewing datatypes, checking missing values, and summarizing statistics using .info() and .describe().

2️⃣ Data Cleaning
Identification of the number of unique values in each column,
Removal of columns not required for analysis,
Creation of a cleaned dataset (df1),
Dropping duplicate rows,
Verifying the revised dataset length.

3️⃣ Visualization & Insights
Several statistical insights were observed during visualization:

📍 Country-wise Restaurant Count
Lowest: Canada – 4 restaurants
Highest: India – 8649 restaurants

📍 Country-wise Total Votes
Lowest: Canada – 412 votes
Highest: India – 1.18716e+06  votes

📍 Rating Category Distribution
Lowest: Poor – 132 restaurants
Highest: Average – 2927 restaurants

📍 Average Rating by Country
Lowest: India – 2.52 average rating
Highest: Philippines – 4.47 average rating


# 📊 Dataset Source: Kaggle 



# 🤝 Contributions
You’re welcome to open issues, suggest improvements, or contribute additional analyses.


# 📲 Linkedin Profile
https://www.linkedin.com/in/himanshi-rai-7483b9313/

