Analyzing the Impact of Social Media on Mental Health

This project investigates how different patterns of social media usage relate to mental health outcomes such as depression, distraction, validation seeking, and emotional well-being. 
Using survey data, we apply exploratory analysis, clustering, predictive modeling, and mediation analysis to uncover behavioral insights.

Files Included

Final_project_UsableAI_project_G4.ipynb — Full notebook containing data processing, analysis, modeling, and visualizations.
smmh.csv — Survey dataset sourced from Kaggle, containing user responses related to social media behavior and mental health indicators.
README.md — Instructions and project overview.

How to Run the Project
Clone the repository:
git clone https://github.com/Vishwajyothireshmi/usable_ai.git
cd usable_ai

Install the required Python libraries:
pip install pandas numpy scikit-learn matplotlib seaborn plotly statsmodels

Launch the Jupyter Notebook:
jupyter notebook Final_project_UsableAI_project_G4.ipynb

Ensure that smmh.csv is in the same directory as the notebook.

Run the notebook cells sequentially to reproduce the analysis and results.

Project Highlights

Data Cleaning & Preprocessing: Standardizing column names, handling missing values.
Exploratory Data Analysis (EDA): Visualizing depression, distraction, and validation seeking trends.
Clustering (KMeans): Classifying users into vulnerable, moderate, and resilient groups based on behavioral indicators.
Supervised Learning Models:
Random Forest
Logistic Regression
Support Vector Machine (SVM)
Platform-specific analyses (Instagram vs Facebook, etc.)
Mediation Analysis: Testing if social comparison mediates the link between time spent and depression.

Requirements

Python 3.7 or higher
Jupyter Notebook
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, plotly, statsmodels

Future Work

Incorporate real-world social media text data for sentiment analysis
Develop advanced predictive models targeting specific mental health outcomes
