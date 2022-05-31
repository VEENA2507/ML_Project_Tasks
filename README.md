# ML_Project_Tasks
ML-InternshipStudio
Internship studio project on machine learning

Project Title: Marketing Campaign for Banking Products

Data Description: The file Bank.xls contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.

Data: https://www.kaggle.com/itsmesunil/bank-loan-modelling/download

Context: The bank has a growing customer base. The bank wants to increase borrowers (asset customers) base to bring in more loan business and earn more through the interest on loans. So , the bank wants to convert the liability based customers to personal loan customers. (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. The department wants you to build a model that will help them identify the potential customers who have a higher probability of purchasing the loan. This will increase the success ratio while at the same time reduce the cost of the campaign.

Attribute Information:

- ID: Customer ID 
- Age: Customer's age in completed years 
- Experience: #years of professional experience 
- Income: Annual income of the customer ($000) 
- ZIP Code: Home Address ZIP code. 
- Family: Family size of the customer 
- CCAvg: Avg. spending on credit cards per month ($000) 
- Education: Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional 
- Mortgage: Value of house mortgage if any. ($000) 
- Personal Loan: Did this customer accept the personal loan offered in the last campaign? 
- Securities Account: Does the customer have a securities account with the bank? 
- CD Account: Does the customer have a certificate of deposit (CD) account with the bank? 
- Online: Does the customer use internet banking facilities? 
- Credit card: Does the customer use a credit card issued by the bank?

Objective: The classification goal is to predict the likelihood of a liability customer buying personal loans.

Steps and Tasks:
1. Import the datasets and libraries, check shape and datatype.
2. Visualise the dataset using plotting using heatmaps and plots. You
can study data distributions for each attribute as well.
3. Clean the dataset by removing missing values and other things.
4. Transform attributes into numerical values and other
necessary transformations
5. Normalise your data and split the data into training, validation and test
set in the appropriate ratio.
6. Use linear regression, Support Vector Regressor for training and get
errors.
7. Use Decision Tree Regressor and Random Forest Regressors.
8. Build an artificial neural network and train it with different layers
and hyperparameters. Experiment a little. Use keras.
9. Pick the best model based on error as well as
generalisation.
10.Save your model and predict on the test set.
