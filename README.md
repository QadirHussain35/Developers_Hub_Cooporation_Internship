Titanic Dataset - Exploratory Data Analysis (EDA)
📌 Overview
This repository contains an Exploratory Data Analysis (EDA) of the Titanic Dataset.
The goal is to analyze, clean, and visualize the dataset to gain insights into passenger survival trends.

📁 Dataset
The dataset contains passenger details like age, fare, gender, class, family size, and survival status.

📌 Source: Titanic Dataset

📝 Columns in the Dataset
Feature	Description
PassengerId	Unique identifier for each passenger
Survived	Survival status (0 = No, 1 = Yes)
Pclass	Ticket class (1st, 2nd, 3rd)
Name	Passenger name
Sex	Gender (Male/Female)
Age	Age of the passenger
SibSp	Number of siblings/spouses aboard
Parch	Number of parents/children aboard
Ticket	Ticket number
Fare	Ticket price
Cabin	Cabin number (if assigned)
Embarked	Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
🛠️ Steps in EDA
1️⃣ Data Cleaning
✅ Handling Missing Values:

Filled missing numeric values (Age, Fare) with their median.

Dropped remaining missing values (Embarked).

✅ Duplicate Removal:

Checked for duplicate records (none found).

✅ Outlier Detection & Removal:

Used boxplots & IQR method to detect outliers in Age, SibSp, Parch, and Fare.

Removed extreme values while preserving meaningful data.

2️⃣ Data Visualization
📊 Bar Charts for Categorical Variables:

Survival Rate: More people did not survive.

Passenger Class: Most passengers were in 3rd class.

Sex Distribution: More males than females.

Embarkation Port: Majority from Southampton (S).

📈 Histograms for Numeric Variables:

Age: Most passengers were aged 20-40 years.

SibSp & Parch: Majority had zero or one family member aboard.

Fare: Highly skewed with some passengers paying very high ticket prices.

🔥 Correlation Heatmap:

Survival is highly correlated with class (higher-class passengers had better survival rates).

Fare and Pclass show a strong positive correlation (higher-class passengers paid more)
