## Datagaurd 
### Application Logs analysis & Predict
Background Knowledge
As per the Security standards any user logs/application logs should not contains Customer specific sensitive data without being masked.

This Project aim at analysis the application logdata from ELK/SPlunk and predict is the pattern that consist of Credit Card number, SSN etc. The final aim of the project is to predict and send email to the log user/producer, alerting them to remove the sensitive information from logging. 

### Technologies Used: 
- Front End: ELK
- Backend: Python for API 
- ML Algorithm - XGBoost
- AWS Cloud S3, Sagemaker

### Project Flow

![](/images/Datagaurd.jpg)

### Decision Tree

Example steps in making prediction in finding a credit card number in logs.

Acronyms Used:

BIN - Bank Identification Number

![](/images/decisionTress.jpg)
