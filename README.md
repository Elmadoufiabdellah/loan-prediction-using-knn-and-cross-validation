# Project Overview
This project focuses on automating the home loan eligibility process for Dream Housing Finance Company. By leveraging customer details provided during online application form submission, the system will determine in real-time whether a customer is eligible for a loan. This solution aims to improve efficiency, accuracy, and customer satisfaction.

# Problem Statement
Dream Housing Finance Company wants to automate the loan eligibility process using customer-provided data. This will enable the company to:

Identify eligible customers more effectively.

Target specific customer segments with personalized offerings.

# Data Description
The company has provided a partial dataset containing customer details such as:

Gender
, Marital Status
, Education
, Number of Dependents
, Income
, LoanAmount
, Credit History

# Objective
Loan approval is a critical aspect of the financial services industry. By leveraging machine learning, we aim to:

Identify factors influencing loan approval.

Visualize the relationships between applicant characteristics and loan approval status.

Develop a machine learning-based solution to predict whether a customer is eligible for a loan based on the provided data.

# Project Workflow

### Data Loading and Inspection:

Load datasets and inspect their structure using pandas.

### Data Cleaning:

Handle missing values by removing rows with NA values.

### Exploratory Data Analysis (EDA):

Analyze distributions, correlations, and trends using matplotlib and seaborn.

### Feature Engineering:

Encode categorical variables using LabelEncoder.

Scale numerical features using StandardScaler.

### Model Development:

Use KNeighborsClassifier for classification.

Validate models using StratifiedKFold cross-validation.

# Evaluation:

Evaluate model performance using accuracy, precision, recall, and F1 score.
