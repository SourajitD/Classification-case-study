# Classification-case-study

Classification - Classifying personal income

Classification is done using Logistic Regression & KNN classifiers, and the accuracy of both the models are compared.

This project is a case study performed as part of NPTEL Online Certification NOC:Python for Data Science, IIT Madras (Jan-Feb 2023).

Problem Statement
- Subsidy Inc. is a company which delivers subsidies to individuals based on their income.
- Accurate income data is one of the hardest piece of data to obtain across the world.
- Subsidy Inc. has obtained a large data set of authenticated data on individual income, demographic parameters, and few financial parameters.
- Subsidy Inc. wishes us to: Develop an income classifier system for individuals.

Objective
- Simplify the data system by reducing the number of variables to be studied, without sacrificing too much of accuracy. Such a system would help Subsidy Inc. in planning subsidy outlay, monitoring and preventing misuse.

Dataset Description:
- The dataset contains 13 columns and 31978 rows.

Variable Description: Numerical-4, Categorial-9
1. age (int) - The age of the individual in years.
2. JobType (string) - The working status of a person i.e. the sector in which the individual works
3. EdType (string) - The level of education
4. maritalstatus (string) - The marital status of the individual
5. occupation (string) - The type of work the individual does
6. relationship (string) - The relationship of the individual to his or her household
7. race (string) - The individual's race
8. gender (string) - The individual's gender
9. capitalgain (int) - The capital gains of the individual
10. capitalloss (int) - The capital losses of the individual
11. hoursperweek (int) - The number of hours that the individual works per week
12. nativecountry (string) - The native country of the individual
13. SalStat (string) - The outcome variable indicating whether a person's salary status <= 50,000 or > 50,000

Solution Conceptualization:
1. Identify if data is clean
2. Look for missing values
3. Identify variables influencing salary status and look for possible relationships between variables
4. Identify if categories can be combined
5. Build a model with reduced number of variables to classify the individual's salary status to plan subsidy outlay, monitoring and preventing misuse

Method Identification:
- Logistic Regression
- K Nearest Neighbors

Realization of solution:
- Evaluate performance metrics
- If assumptions are satisfied and solutions acceptable than model is good
