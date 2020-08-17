# Predicting-credit-card-approvals

Project Description
Commercial banks and Financial services firms receive a lot of applications for
credit cards. Many of them get rejected for many reasons, like high loan balances,
low-income levels, or too many inquiries on an individual's credit report, for
example. Manually analyzing and approving these applications on the basis of those
attributes is very error-prone and time-consuming.
So, we have basically tried to automate the whole process of approval of credit card
applications using machine learning models similar to what most of the banks do.
The datasets contained 15 features(information about the person applying) and
through the model, we found that there are four features that affects the approval
decision while others have very less or no impact. The four factors all positively
affect the outcome and that as these factors increase, so does the probability that a
credit card will be issued.
The four influencing factors are:
● Prior default,
● Years employed,
● Credit score, and
● Income level.
Other variables such as age, sex, or ethnicity did not have an influence on whether
the application was denied. A Chi-Squared test for independence validated our
conclusion Ethnicity and Approval status are independent.
Machine learning models
While building this credit card predictor, we tackled some of the most
widely-known preprocessing steps such as scaling, label encoding, and missing
value imputation.
We have used Logistic Regression model to come up with the solution and the
reason for selecting this model is because linear regression models are useful for
predicting continuous (numeric) variables. However, the target value in Approved is
binary and can only be values of 1 or 0. The applicant can either be issued a credit
card or denied- they cannot receive a partial credit card. We could use linear
regression to predict the approval decision using threshold and anything below
assigned to 0 and anything above is assigned to 1. Unfortunately, the predicted
values could be well outside of the 0 to 1 expected range. Therefore, linear or
multivariate regression will not be effective for predicting the values. Instead,
logistic regression will be more useful because it will produce a probability that the
target value is 1. Probabilities are always between 0 and 1, so the output will more
closely match the target value range than linear regression.
We finished with the machine learning model to predict if a person's application for
a credit card would get approved or not given some information about that person.
The model, we built was able to predict the outcome of a credit application with
85.21% accuracy which was significantly better performance than the baseline
model.
