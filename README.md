🏡🏡 𝐇𝐨𝐮𝐬𝐞 𝐏𝐫𝐢𝐜𝐞𝐬 𝐄𝐃𝐀 – 𝐃𝐚𝐭𝐚 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐏𝐡𝐚𝐬𝐞

Welcome to the exploratory data analysis (EDA) phase of the House Prices - Advanced Regression Techniques project. This notebook is focused on understanding the structure, patterns, and relationships within the data to lay a solid foundation for the upcoming feature engineering and model building phases.

📂 𝐃𝐚𝐭𝐚𝐬𝐞𝐭 𝐔𝐬𝐞𝐝

File: train.csv

Source: Kaggle - House Prices: Advanced Regression Techniques

Rows: 1460

Columns: 81

Target Variable: SalePrice

📊 𝗢𝗯𝗷𝗲𝗰𝘁𝗶𝘃𝗲𝘀 𝗼𝗳 𝗧𝗵𝗶𝘀 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀

Identify and visualize missing values.

Understand numerical and categorical features.

Explore distribution patterns of variables.

Detect outliers in numerical variables.

Investigate cardinality of categorical features.

Analyze temporal (year-based) trends.

Study relationships between independent features and SalePrice.

🔍 𝗞𝗲𝘆 𝗦𝘁𝗲𝗽𝘀 𝗣𝗲𝗿𝗳𝗼𝗿𝗺𝗲𝗱
✅ Data Loading and Setup
Loaded the dataset using pandas.

Enabled full column visibility and added scrollable DataFrame display.

🔎 Missing Values
Calculated total and percentage of missing values.

Visualized their impact on SalePrice.

Found that some missing values strongly correlate with price — will be carefully handled during feature engineering.

🔢 𝗡𝘂𝗺𝗲𝗿𝗶𝗰𝗮𝗹 𝗩𝗮𝗿𝗶𝗮𝗯𝗹𝗲𝘀
Identified all numeric columns.

Separated year features for further analysis.

⏳ 𝗧𝗲𝗺𝗽𝗼𝗿𝗮𝗹 𝗩𝗮𝗿𝗶𝗮𝗯𝗹𝗲𝘀
Investigated the influence of variables like YearBuilt, YearRemodAdd, etc.

Observed relationships with SalePrice using scatter plots.

🧮 𝗗𝗶𝘀𝗰𝗿𝗲𝘁𝗲 𝘃𝘀 𝗖𝗼𝗻𝘁𝗶𝗻𝘂𝗼𝘂𝘀 𝗙𝗲𝗮𝘁𝘂𝗿𝗲𝘀
Discrete Features: Few unique values, visualized using bar plots.

Continuous Features: Broad value range, visualized with histograms.

📌 𝗟𝗶𝗯𝗿𝗮𝗿𝗶𝗲𝘀 𝗨𝘀𝗲𝗱
python
pandas        # For data manipulation
numpy         # For numerical operations
matplotlib    # For plotting
seaborn       # For advanced visualizations
📈 𝗦𝗮𝗺𝗽𝗹𝗲 𝗩𝗶𝘀𝘂𝗮𝗹𝘀
Missing Value Impact

Median SalePrice per Feature

Year Sold vs SalePrice Line Plot

Scatter Plots: Year Features vs SalePrice

Bar Charts: Discrete Features vs SalePrice

Histograms: Continuous Features

📌 𝗢𝗯𝘀𝗲𝗿𝘃𝗮𝘁𝗶𝗼𝗻𝘀
Missing values can significantly influence SalePrice and must be treated thoughtfully.

Some year-related features, when transformed, show strong trends with price.

Discrete features like OverallQual, OverallCond, etc., have strong predictive potential.

Continuous features vary widely in distribution and require normalization/scaling later.

📦 𝗡𝗲𝘅𝘁 𝗦𝘁𝗲𝗽𝘀
Handle missing values smartly (based on their observed impact).

Perform feature engineering on temporal and categorical variables.

Prepare data for machine learning models.

🙌 𝗔𝘂𝘁𝗵𝗼𝗿 𝗡𝗼𝘁𝗲𝘀
This project is a part of my data science journey to understand feature behavior and improve prediction accuracy. Feedback and suggestions are always welcome!
