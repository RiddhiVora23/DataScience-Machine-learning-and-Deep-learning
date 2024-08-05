# **ML Data Cleaning and Feature Selection**

**Problem Statement**: Implementing a Dataset-Bank Personal Loan Modeling for predictive learning, analyzing the data's accuracy, and identifying the key features.

## **Abstract**
This dataset contains information about 5000 customers, including demographics, banking relationships, and responses to a personal loan campaign. Only 9.6% of these clients accepted the loan. The key objective is to clean the data, perform feature selection, and build predictive models.

## **Data Attributes**
- **ID**: Customer ID
- **Age**: Customer's age
- **Experience**: Years of professional experience
- **Income**: Annual income ($000)
- **ZIP Code**: Home ZIP code
- **Family**: Family size
- **CCAvg**: Avg. monthly credit card spending ($000)
- **Education**: Education level (1: Undergrad, 2: Graduate, 3: Advanced/Professional)
- **Mortgage**: Value of house mortgage ($000)
- **Personal Loan**: Accepted personal loan (1: Yes, 0: No)
- **Securities Account**: Has securities account (1: Yes, 0: No)
- **CD Account**: Has certificate of deposit account (1: Yes, 0: No)
- **Online**: Uses internet banking (1: Yes, 0: No)
- **Credit Card**: Uses bank's credit card (1: Yes, 0: No)

## **Key Steps**

### Data Loading and Initial Inspection
- Import libraries and dataset
- Check data types and descriptive statistics

### Data Cleaning
- Identify and handle negative values in 'Experience'
- Check and handle missing values

### Exploratory Data Analysis (EDA)
- Plot density curves for numeric variables
- Correlation matrix to understand dependencies

### Feature Selection
- OLS Regression to identify significant features
- Permutation Importance with Random Forest

### Data Splitting
- Split data into training and test sets

### Model Building and Evaluation
- Logistic Regression
- XGBoost Classifier
- Random Forest Classifier
- Assess model performance with confusion matrix and accuracy scores

### Outlier Detection and Handling
- Identify and remove outliers in 'CCAvg' and 'Mortgage'

### Imputation
- Use median, mean, and mode imputation to handle missing values

## **Conclusion**
The analysis revealed that all independent variables are significant, with 'Income' having the most impact on loan acceptance.