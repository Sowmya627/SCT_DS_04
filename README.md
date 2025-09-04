# SCT_DS_04

# 📁 Dataset

Source: Kaggle / US Accidents Dataset (2016–2023)
Dataset: US_Accidents_March23.csv

This dataset contains information about road traffic accidents in the United States, with details about location, time, weather, and other contributing factors.


---

# ⚙ Steps Followed

# 1. Data Preparation

Load the dataset from a ZIP archive.

Explore the dataset: shape, data types, and missing values.

Handle missing values and perform basic cleaning.

Extract datetime features (hour, day of week, month).


# 2. Exploratory Data Analysis (EDA)

Countplot for accident severity to check class distribution.

Distribution of accidents across time (hour, day, month).

Check weather and road conditions related to accidents.

Identify accident hotspots by state and city.


# 3. Data Preprocessing

Encode categorical variables (e.g., weather condition, state).

Select features related to time, road, and weather.

Scale numerical features if needed.

Split into train and test sets.


# 4. Model Building

Train classification models to predict severity of accidents.

# Models used:

DecisionTreeClassifier (max_depth=6 for interpretability).

RandomForestClassifier (for better accuracy).



# 5. Model Evaluation

Metrics used:

Accuracy

Classification Report

Confusion Matrix


Visualized confusion matrix and performance metrics.


# 6. Feature Importance

Identify most important features contributing to accident severity:

Weather condition

Visibility

Hour of day

Road surface condition


Plot feature importances for insights.


# 7. Accident Hotspots

Visualize states and cities with highest accident counts.

Plot heatmaps to identify geographical hotspots.

Time-series plots to analyze accident trends.


# 8. Cross-Validation

Perform 5-fold cross-validation to ensure model stability.

Report individual scores and mean accuracy.


# 🔧 Tools & Libraries Used

Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn



---

# 📌 How to Run

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Run the script (in Colab or locally):

python traffic_accident_analysis.py


--
