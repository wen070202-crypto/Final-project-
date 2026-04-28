# Final Project: Titanic Survival Data Analysis

## Project Purpose

The purpose of this project is to demonstrate proficiency in using Python for data analysis. This project uses Python to import, clean, manipulate, analyze, visualize, and model Titanic passenger data in order to better understand which factors were related to passenger survival.

The analytical objective of this project is to examine survival patterns based on passenger characteristics such as sex, passenger class, age, fare, and family size.

## Research Questions

1. What was the overall survival rate of passengers in the dataset?
2. Did passenger sex affect survival rate?
3. Did passenger class affect survival rate?
4. How were age, fare, and family size related to survival?
5. Can a simple machine learning model predict passenger survival?

## Dataset

The dataset used in this project is the Titanic passenger dataset. It includes passenger information such as passenger class, name, sex, age, number of siblings/spouses aboard, number of parents/children aboard, ticket fare, port of embarkation, and whether the passenger survived.

The dataset file should be placed in the following location:

```text
data/titanic.csv
```

## Python Libraries Used

This project uses the following Python libraries:

1. pandas
2. numpy
3. matplotlib
4. seaborn
5. scipy
6. scikit-learn

## Project Files

```text
final-project/
|
|-- README.md
|-- requirements.txt
|-- ai_chat_log.md
|
|-- data/
|   |-- titanic.csv
|
|-- notebooks/
    |-- final_analysis.ipynb
```

## Methods

The project follows these steps:

1. Import Python libraries
2. Load the Titanic dataset
3. Inspect the dataset
4. Clean missing values
5. Create new variables
6. Analyze survival patterns
7. Visualize the data
8. Conduct a statistical test
9. Build a logistic regression model
10. Summarize findings

## Key Findings

The analysis found that survival was strongly related to sex and passenger class. Female passengers had a much higher survival rate than male passengers. First-class passengers also had a higher survival rate than second- and third-class passengers. Fare and passenger class were related to survival outcomes, while age and family size also provided useful information.

The logistic regression model showed that passenger sex, passenger class, age, fare, and family size can be used to predict survival with reasonable accuracy.

## How to Run This Project

1. Clone or download this repository.
2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/final_analysis.ipynb
```

4. Run all cells from top to bottom.

## Individual Contribution

This was an individual project. I completed all parts of the project, including dataset selection, data cleaning, data analysis, visualizations, statistical testing, machine learning modeling, README writing, and GitHub organization.

## Generative AI Use

Generative AI was used to help organize the project structure, draft the README file, and create sample Python code for data analysis. A record of AI assistance is included in `ai_chat_log.md`.
