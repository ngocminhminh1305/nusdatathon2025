# Corporate Ownership Classification

## Background
In today’s globalized economy, understanding corporate ownership and influence is critical for businesses, investors, and regulators. Companies operate within complex hierarchies, with entities spanning local (domestic) and international (global) levels. Identifying whether a company is a Domestic Ultimate or a Global Ultimate provides actionable insights into its operational independence, global reach, and decision-making power.

Predicting corporate ownership structures enables competitive analysis, investment decisions, and merger & acquisition strategies by revealing a company's independence, financial backing, and decision-making hierarchy.

## Problem Statement
Your challenge is to develop a robust machine learning model to predict the "Is Domestic Ultimate" and "Is Global Ultimate" classifications for companies based on their operational, financial, and structural characteristics. Using the given dataset, your model should provide accurate predictions for these two target variables.

## Data Dictionary
The dataset consists of the following attributes:

- **AccountID**: A distinctive label or number assigned to a specific account within a system or organisation.
- **Company**: Company name.
- **SIC Code**: Standard Industrial Classification (SIC) code is a numerical system used to classify and categorise industries based on their primary economic activities.
- **Industry**: Specific sector of economic activity.
- **8-Digit SIC Code**: A numerical code system used to classify and categorise industries based on their primary business activities.
- **8-Digit SIC Description**: Description of the 8-digit SIC code.
- **Year Found**: Year in which an entity, such as a company or organisation, was founded or established.
- **Parent Company**: A corporation or another form of business entity that owns or controls another company.
- **Parent Country**: The country of origin or the home country of a multinational corporation or a company that has subsidiaries or operations in multiple countries.
- **Ownership Type**: The classification or categorization of the legal structure that dictates how a business entity is owned, managed, and organised.
- **Company Description**: A concise and informative overview that provides key details about a business entity.
- **Square Footage**: A unit of measure used to quantify the total area or size of a two-dimensional space.
- **Company Status (Active/Inactive)**: The current standing or operational condition of a business entity, indicating whether it is currently active and conducting business or inactive.
- **Employees (Single Site)**: The total number of individuals employed by a company at a specific location or site.
- **Employees (Domestic Ultimate Total)**: The total number of individuals employed by a company across all its domestic or home-country operations.
- **Employees (Global Ultimate Total)**: The total number of individuals employed by a company across all its global operations (excluding Domestic).
- **Sales (Domestic Ultimate Total USD)**: The total sales revenue generated by a company within its domestic or home country operations, measured in U.S. dollars.
- **Sales (Global Ultimate Total USD)**: The total sales revenue generated by a company on a global scale, measured in U.S. dollars (excluding Domestic).
- **Import/Export Status**: The classification of a company based on its involvement in international trade, specifically with regard to importing and exporting goods.
- **Fiscal Year End**: The conclusion of a company's accounting and financial reporting period.
- **Is Domestic Ultimate**: A categorical attribute or indicator that signifies whether a particular entity or company is the ultimate or highest-level company within a corporate structure based in its home country.
- **Is Global Ultimate**: A categorical attribute or indicator that signifies whether a particular entity or company holds the status of being the ultimate or highest-level company within a corporate structure on a global scale.

*Note: The dataset cannot be made public due to restrictions imposed by the organizers.*

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

