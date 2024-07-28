# ipl-data-analysis-apache-spark-project

📊 Dataset:
The dataset used for this project included detailed information from IPL matches, such as ball-by-ball details, player statistics, and match results. The data was read from an S3 bucket and processed using Spark's powerful capabilities.

🛠️ Data Processing and Analysis:
- Spark Session Creation: Initiated a Spark session to manage the data processing tasks.
- Data Ingestion: Loaded the IPL dataset from an S3 bucket using Spark’s CSV reader with schema inference and manual schema definition for consistency.
- Data Cleaning: Cleaned the dataset by handling null values, ensuring data types were correct, and removing inconsistencies.
- Exploratory Data Analysis (EDA): Conducted EDA to uncover patterns and relationships within the data, such as run distributions, player performance metrics, and team statistics.
- Advanced Analytics: Performed advanced data processing tasks including aggregations, window functions, and joins to derive deeper insights.

💡 Key Insights:
- Team Performance Trends: Analyzed how different teams performed across various seasons.
- Top Players: Identified top-performing players based on runs scored, wickets taken, and other critical metrics.
- Match Outcome Factors: Discovered key factors that influenced match outcomes, such as the impact of the toss, batting first vs. second, and player contributions.
