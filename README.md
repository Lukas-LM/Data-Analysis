# Data Analysis

This project is a data analysis on a diabetes diagnoses dataset.
The goal is to analyse the dataset whether it is suitable for a Machine Learning model or not.

## Project Overwie
- **Type**: Data analysis with Python
- **Dataset**: Prima Indians Diabetes Dataset from Kaggle
- **Language**: Python
- **Libraries**: NumPy, Pandas, Scikit-Learn, Matplotlib
- **Tools**: GPT-5 mini, Google Locker Studio

## Workflow

### Using Generative AI

- prompting Python functions to clean a dataset

possible data preprocessing functions:
- checking and cleaning missing values
- checking and cleaning wrong datatypes
- checking and cleaning outliers
- checking and cleaning duplicates
- cleaning invalid zero values
- scaling numeric columns and normalizing categorical columns

### Data Preprocessing with GPT-5 mini

- cleaning invalid zero values
- scaling numeric columns and normalizing categorical columns

### Making the cleaned data usable

- exporting the dataset with pandas to a cleaned csv dataset

### Creating a Dashboard

- looking for good and meaningful visualizations
    - Number of rows
    - Pie Chart for Outcome-balance
    - Bar Chart for Feature-Cleaning
    - Heatmap for Correlation matrix
- creating the Dashboard in Google Locker Studio
- arrange the charts and graphs
- give the visualizations a unifrom look

### Analyse the dataset

- 768 rows are not enough for a good trained Machine Learning Model
- the cleaning of the invalid zero values would have been a big impact on the model because most of the values are replaced by the mean
- there are not much columns that correlated to the target column 'Outcome'
- All in all the dataset is not optimal for a Machine Learning Model

## Structure
Gen_AI_Data_Cleaning/ │ ├── data/ │ ├── raw/ │ │ └── diabetes.csv │ └── processed/ │ └── Cleaned_data.csv │ ├── src/ │ └── gen_ai_cleaning.py │ ├── dashboard/ │ └── Diabetes_Dataset_Dashboard.pdf │ ├── docs/ │ ├── Dashboard_analysis.txt │ ├── prompts.txt │ └── requirements.txt │ └── README.md

## My path

I learned new technologies to analyse data.
In addition to deepening my data cleaning skills, I learned how to use Google Locker Studio, as well as creating a Dashboard
Gen AI is a very often used technology in data anlysis, that is why I tried to use it in one of my projects to experience the full data anlyst profile
Also the analyzation of a data is a mainskill what I learned
I learned:
- the funktion of Google Locker Studio
- creating a Dashboard
- using a LLM to clean data
- analyzing data
