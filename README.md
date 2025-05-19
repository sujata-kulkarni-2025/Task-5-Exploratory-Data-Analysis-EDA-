# Task-5-Exploratory-Data-Analysis-EDA

🧾 Dataset Summary:
•	Rows: 891
•	Columns: 12
•	Target Variable: Survived (0 = No, 1 = Yes)
📊 Column Overview:
Column	Description	Nulls
PassengerId	Unique ID for each passenger	No
Survived	Survival status (0 = No, 1 = Yes)	No
Pclass	Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)	No
Name	Passenger name	No
Sex	Gender	No
Age	Age in years	Yes (177 missing)
SibSp	# of siblings/spouses aboard	No
Parch	# of parents/children aboard	No
Ticket	Ticket number	No
Fare	Passenger fare	No
Cabin	Cabin number	Yes (687 missing)
Embarked	Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)	Yes (2 missing)
Next, I’ll perform the Exploratory Data Analysis (EDA), including:
1.	Summary statistics
2.	Missing values
3.	Distribution plots (Age, Fare, etc.)
4.	Survival analysis by category (Sex, Pclass, Embarked, etc.)
Proceeding with EDA... 
 
🔍 Exploratory Data Analysis (EDA) Summary (So Far)
📉 Missing Values:
•	Age: 177 missing
•	Cabin: 687 missing — over 75% missing, likely unusable without heavy imputation
•	Embarked: 2 missing
📊 Numerical Summary:
Feature	Mean	Std Dev	Min	25%	50%	75%	Max
Age	29.7	14.5	0.42	20.1	28	38	80
Fare	32.2	49.7	0	7.9	14.5	31	512
SibSp	0.52	1.10	0	0	0	1	8
Parch	0.38	0.81	0	0	0	0	6
🧍‍♂️ Categorical Features:
•	Sex: 577 male, 314 female
•	Pclass: Most passengers in 3rd class
•	Embarked: Most from Southampton (S)
Next, I’ll visualize key features and survival relationships:
1.	Survival rate by gender, class
2.	Distribution plots for Age and Fare
3.	Correlation heatmap
Proceeding with visualizations... 
 
📊 Key Visual Insights from EDA
1. Survival Count
•	About 38% survived, while 62% did not.
2. Survival by Sex
•	Females had a significantly higher survival rate than males.
•	Most males did not survive.
3. Survival by Pclass
•	1st class passengers had the highest survival rate, followed by 2nd, then 3rd.
•	3rd class had the lowest survival rate.
4. Age Distribution
•	Most passengers were between 20–40 years old.
•	A few infants and elderly passengers were also present.
5. Fare Distribution
•	Most fares were below 50, with a few high-end outliers above 250.
•	Fare is positively skewed.
6. Correlation Heatmap
•	Fare and Pclass are negatively correlated (higher class, higher fare).
•	Survival correlates positively with Fare and negatively with Pclass.
