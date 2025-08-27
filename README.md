# Titanic: Survival Analysis and Prediction

This project performs an in-depth analysis of the classic Titanic dataset to identify key factors that influenced passenger survival. After a thorough exploratory data analysis (EDA), a machine learning model is trained to predict whether a passenger would have survived the disaster.

## Project Goal

The primary goal is to use data analysis and machine learning techniques to explore the Titanic dataset and build a predictive model. The project demonstrates a full data science workflow, including data cleaning, feature engineering, exploratory data analysis, and model building.

## Technology Stack

* **Data Analysis**: Python, Pandas, NumPy
* **Data Visualization**: Matplotlib, Seaborn
* **Machine Learning**: Scikit-learn
* **Environment**: Jupyter Notebook

##  Project Workflow

The project follows a structured data science methodology:
1.  **Data Loading & Initial Inspection**: The dataset is loaded into a pandas DataFrame, and its structure, data types, and missing values are examined.
2.  **Data Cleaning & Preprocessing**: Missing values (e.g., in the 'Age' column) are handled, and categorical features like 'Sex' and 'Embarked' are converted into a numerical format suitable for modeling.
3.  **Exploratory Data Analysis (EDA)**: Visualizations are created to uncover relationships between passenger attributes (like class, sex, and age) and their survival outcome.
4.  **Modeling & Evaluation**: The data is split into training and testing sets. A Logistic Regression model is trained to classify passengers, and its performance is evaluated based on its accuracy.

## Key Insights from EDA

* **Gender**: Female passengers had a significantly higher rate of survival than male passengers.
* **Passenger Class**: First-class passengers had a much higher chance of survival compared to those in second and third class.
* **Age**: Children had a higher survival rate than adults, aligning with the "women and children first" protocol.

## How to Run

To run this analysis on your local machine, follow these steps:

**1. Clone the Repository**
```bash
git clone [https://github.com/YourUsername/Titanic-Survival-Analysis.git](https://github.com/YourUsername/Titanic-Survival-Analysis.git)
cd Titanic-Survival-Analysis
```

**2. Set Up a Virtual Environment and Install Dependencies**
```bash
# Create and activate the environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install the required libraries
pip install -r requirements.txt
```

**3. Launch Jupyter Notebook**
```bash
jupyter notebook
```
From the Jupyter interface in your browser, open the `EDATitanic.ipynb` file to view and run the analysis.
