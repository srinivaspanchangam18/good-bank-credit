# Bank Credit Risk Prediction

## Project Overview

This project focuses on applying data science and machine learning techniques to bank credit risk prediction. The objective is to explore banking-related data, prepare meaningful features, and develop predictive models to support credit risk analysis.

The project demonstrates a structured machine learning workflow, from data preparation and exploratory data analysis to feature engineering, model development, and evaluation.

## Objectives

- Understand and explore banking-related datasets.
- Perform data cleaning and preprocessing.
- Combine information from multiple data sources where appropriate.
- Apply feature engineering techniques to prepare model inputs.
- Develop predictive machine learning models.
- Evaluate model performance using appropriate metrics.

## Dataset

The project works with three datasets:

- **Account Data:** Account-related information.
- **Enquiry Data:** Credit enquiry-related information.
- **Demographics Data:** Customer demographic information.

The datasets are kept separate from this public repository to protect data privacy and confidentiality.

## Technologies Used

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook
- **Visualization:** Matplotlib, Seaborn, where applicable

## Project Workflow

1. **Data Loading:** Import the account, enquiry, and demographic datasets.
2. **Exploratory Data Analysis:** Examine the data structure, distributions, missing values, and relevant patterns.
3. **Data Preprocessing:** Clean and transform the data for analysis.
4. **Feature Engineering:** Create and prepare features for predictive modelling.
5. **Model Development:** Train the machine learning models implemented in the notebook.
6. **Model Evaluation:** Assess model performance using the evaluation methods implemented in the notebook.
7. **Interpretation:** Review the findings and consider their implications for credit risk analysis.

## Repository Structure

```text
bank-credit-risk-prediction/
│
├── README.md
├── bank_credit_risk_prediction.ipynb
├── requirements.txt

The `data/` directory is shown for illustration and should not contain private datasets in the public repository.

## How to Run the Project

### 1. Clone the repository

```bash
git clone <YOUR-REPOSITORY-URL>
cd bank-credit-risk-prediction
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install the dependencies

If the repository includes a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

Otherwise, install the packages required by the notebook.

### 4. Prepare the datasets

Place the authorized CSV files in a local `data/` directory:

- `account.csv`
- `enquiry.csv`
- `demographics.csv`

Ensure that the file paths in the notebook match your local directory structure.

### 5. Run the notebook

```bash
jupyter notebook
```

Open the project notebook and execute the cells in sequence.

**Note:** Previously saved notebook outputs can be viewed without rerunning the analysis, but reproducing the results requires the datasets and dependencies.

## Key Learning Areas

This project provides practical experience with:

- Working with multiple related datasets.
- Data cleaning and preprocessing.
- Exploratory data analysis.
- Feature engineering.
- Machine learning workflows.
- Model evaluation and interpretation.
- Responsible handling of sensitive data.

## Limitations

Credit risk prediction is a high-impact application. The usefulness of a model depends on data quality, the target definition, appropriate validation, and careful evaluation. Additional fairness testing, explainability, governance, and domain validation would be required before using a model for real financial decisions.

This project is intended for learning and portfolio demonstration, not as a production-ready credit approval system.

## Author

**Srinivas Panchangam**

- LinkedIn: [Your LinkedIn Profile](YOUR-LINKEDIN-PROFILE-URL)
