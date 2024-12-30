# Telecom-Churn-Analysis
Dataset Link:   https://www.kaggle.com/datasets/blastchar/telco-customer-churn
**csv file is not getting uploaded so use above link to download it from Kaggle**

import kagglehub
# Download latest version
path = kagglehub.dataset_download("blastchar/telco-customer-churn")
print("Path to dataset files:", path)


Analyzed customer churn patterns by contract type, revealing that month-to-month contracts had a churn rate of 42%, compared to 11% for yearly and 3% for two-year contracts, suggesting the value of long-term subscription.
Investigated payment method trends, identifying a significant correlation between electronic checks and a 45% churn rate, recommending strategies to encourage the adoption of more secure and reliable payment methods.
