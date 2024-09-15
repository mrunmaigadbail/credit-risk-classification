# credit-risk-classification

Purpose of the analysis is to predict healthy loan and high-risk loan on the given loan data set. In the dataset we have given Loan size, interest rate, borrowers income, debt to income ratio, number of accounts, derogatory marks, total debt, and loan status. we used value_counts on loan status and found out data is imbalanced as we got 0(healthy loan) as 75036 and 1(high risk loan) 2500.

To start machine learing we separated data in labels which is loan status and feauters all other data in dataset. We used Logistic regression model and fit the model with training data. To get prediction we used features test data.

The accuracy measures gives the overall correctness of a model's predictions which we got 99.39%. While precision focuses on the accuracy of positive predictions which we got 100 % for 0(healthy loan) and 87% for 1(high risk loan). Recall evaluates how well the model identifies all actual positive instances we got 100 % for 0(healthy loan) and 95% for 1(high risk loan)

So our model is better at predicting healthy loan than high-risk loan but our model is also good as we prediced only 32 wrong from 625. Predicition of high risk loan is more important as it may cause loss to financial company if predicied wrong. So we can try to use other model to check if we improve on predicting high risk loans.