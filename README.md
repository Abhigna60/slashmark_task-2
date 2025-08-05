# slashmark_task-2
🚢 Titanic Data Analysis & Visualization
This project performs exploratory data analysis (EDA) on the Titanic dataset using Python. It includes data cleaning, statistical summaries, and insightful visualizations to better understand factors that influenced passenger survival.

📁 Dataset
The dataset contains information about passengers aboard the RMS Titanic, including:

Passenger demographics (age, sex, class)

Ticket and cabin details

Whether or not they survived

The CSV file used is assumed to be named titanic.csv.

📊 Project Highlights
✅ Features:

Data loading and inspection

Handling missing values in Age and Embarked

Statistical summaries and correlation analysis

Visualizations using Seaborn & Matplotlib

Survival rate analysis by class and gender

🖼 Visualizations Included
📈 Histogram + KDE plot of Age distribution

📊 Count plot of survival (0 = Died, 1 = Survived)

📦 Box plot of Age by Passenger Class

🔥 Correlation heatmap of numerical features

📌 Survival Insights
The script also calculates and prints:

🔹 Survival rate by passenger class

🔹 Survival rate by gender

🛠 Requirements
Make sure you have the following Python libraries installed:


pip install pandas numpy matplotlib seaborn
▶ How to Run
Place titanic.csv in your working directory.


🧠 How It Works
The script performs the following steps:

Loads the Titanic dataset using Pandas

Prints dataset info, missing values, and statistical description

Fills missing Age values with the mean, and Embarked with the mode

Creates multiple visualizations using Seaborn and Matplotlib

Prints survival rates by class and gender


📄 License
This project is licensed under the MIT License.
