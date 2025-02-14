# Corporate Ownership Classification

## Overview
In today’s globalized economy, understanding corporate ownership and influence is crucial for businesses, investors, and regulators. Companies operate within complex hierarchies that span both local (domestic) and international (global) levels.

This project aims to develop a robust machine learning model to predict the corporate ownership classification of companies. Specifically, the model predicts:

1. **Is Domestic Ultimate** – Identifies whether a company is the highest-level entity within its home country.
2. **Is Global Ultimate** – Identifies whether a company is the highest-level entity within a global corporate structure.

The model leverages various operational, financial, and structural characteristics of companies to determine their ultimate ownership status.

## Problem Statement
Predicting corporate ownership structures enables better decision-making for:
- Competitive analysis
- Investment decisions
- Mergers and acquisitions

Our goal is to build an accurate machine learning model that classifies companies based on their ownership structure using a dataset with rich financial and structural information.

## Dataset
The dataset consists of various features that provide insights into a company's operations and ownership. Key attributes include:

- **AccountID**: Unique identifier for the company.
- **Company Name**: Name of the company.
- **SIC Code** & **8-Digit SIC Code**: Industry classification.
- **Year Founded**: Establishment year of the company.
- **Parent Company** & **Parent Country**: Information about parent entity.
- **Ownership Type**: Legal structure classification.
- **Company Status**: Active or inactive status.
- **Number of Employees** (Single Site, Domestic, Global): Workforce distribution.
- **Sales Revenue** (Domestic, Global): Financial performance.
- **Import/Export Status**: International trade involvement.
- **Fiscal Year End**: Accounting period end.
- **Is Domestic Ultimate**: Target variable indicating domestic ownership hierarchy.
- **Is Global Ultimate**: Target variable indicating global ownership hierarchy.

## Installation
To set up the project, ensure that the `requirements.txt` file is present in the root directory. Run the following command to install all necessary dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
This project requires the following libraries:
- **numpy** (1.26.3) - Numerical computations
- **pandas** (2.1.4) - Data manipulation and analysis
- **sklearn** (1.6.0) - Machine learning utilities
- **matplotlib** (3.8.2) - Data visualization
- **seaborn** (0.13.1) - Statistical data visualization
- **xgboost** (2.1.3) - Gradient boosting framework
- **scipy** (1.14.1) - Scientific computing
- **tensorflow** (2.18.0) - Deep learning framework

## Usage
1. Preprocess the dataset and perform exploratory data analysis (EDA).
2. Train machine learning models to predict the `Is Domestic Ultimate` and `Is Global Ultimate` classifications.
3. Evaluate performance using appropriate metrics (e.g., accuracy, precision, recall, F1-score).
4. Use the trained model for corporate structure analysis and insights.

## Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request.

## License
This project is open-source and available under the MIT License.

---

For any questions or issues, please contact the repository maintainers.

