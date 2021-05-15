# My Machine Learning Journey
This repository contains a brief description of the projects which has been completed. More new and interesting projects will be updated along the way. 

# Content

### Project 1: Predicting house prices

#### Case Study:

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts.

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

Which variables are significant in predicting the price of a car How well those variables describe the price of a car Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the Americal market

#### Objective:

To build a model of the price of cars with the available independent variables to understand how exactly the prices vary with the independent variables. This will help in making an informed decision by the automobile company

#### ML Modelling:

For this particular project linear regression model was used to predict the car prices. The metric used in this particular project is `r2_score`.

### Project 2: Telecom Churn Case Study

#### Case Study:

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

#### Objective:

To analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

#### ML Modelling:

For this particular project two models were used- Logistic Regression and Reandom Forest Classifier. The metric used for this particular project is: `confusion matrix`  

### Lead Scoring Case Study

#### Case Study:
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.

#### Objective:
Build a model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

#### ML Modelling:

For this particular project Logistic regression was used. The metrics used for this particular project are: `confusion matrix` and `ROC Curve`.

### Credit Card Fraud Detection

#### Problem Statement:
For many banks, retaining high profitable customers is the number one business goal. Banking fraud, however, poses a significant threat to this goal for different banks. In terms of substantial financial losses, trust and credibility, this is a concerning issue to both banks and customers alike.

It has been estimated by Nilson report that by 2020 the banking frauds would account to $30 billion worldwide. With the rise in digital payment channels, the number of fraudulent transactions is also increasing with new and different ways.

In the banking industry, credit card fraud detection using machine learning is not just a trend but a necessity for them to put proactive monitoring and fraud prevention mechanisms in place. Machine learning is helping these institutions to reduce time-consuming manual reviews, costly chargebacks and fees, and denials of legitimate transactions.

#### Understanding and Defining Fraud
Credit card fraud is any dishonest act and behaviour to obtain information without the proper authorization from the account holder for financial gain. Among different ways of frauds, Skimming is the most common one, which is the way of duplicating of information located on the magnetic strip of the card.

Apart from this, the other ways are:

Manipulation/alteration of genuine cards, Creation of counterfeit cards, Stolen/lost credit cards, and Fraudulent telemarketing

#### Objective:
To predict fraudulent credit card transactions with the help of machine learning models.

#### ML Modelling:

For this particular projects the models used are: Logistic Regression, xg Boost, Ramdom Forest Classifier. Also as this dataset was highly imbalanced, the techniques used to get a more balanced dataset are: `Random Oversampling`, `SMOTE`, `ADASYN`. The metrics used for this particular project are: `roc_auc_score`, `roc_curve`, and `F1 Score`.

### Image Classification For Visually Disabled People

<Will be uploaded soon>
  
### Predicting Fatigue Score Of The Employees

<Will be uploaded soon>
  
#### Step-by-step description:

a. Understanding the dataset 

b. Cleaning and preparing the dataset

c. Visualizing the dataset

d. Predicting the dataset
