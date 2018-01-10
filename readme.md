# My first machine learning project

### Introduction: 

### In this project, I will be looking at a typical imbalanced binary classification problem\* where the number of responses in the negative class greatly outweighs that of the positive class, and taking a look at a few machine learning algorithms that are used in these cases. 

\*Fortunately for me, I have the opportunity to work on a real world dataset and this challenge led me to many new insights to the world of machine learning and data science. That said, due to the sensitivity of this information, I will be anonymising ALL of the important features and information that will be presented in this project, as you will see later.

### Background:
This project will be looking at a company that provides an online restaurant reservation service. With its natively developed online platform, this company offers its users the ability to instantly reserve restaurants ahead of time on a 24/7 basis and also provides diners with a hassle-free dining experience via its seating and queue management technologies.

One usual product/feature offered by this sort of companies are discount vouchers. These vouchers adds as an incentive for customers to utilise the company’s reservation platform and also helps to introduce new restaurants to customers. Typically, these vouchers are bought along with the reservation of the restaurant.

### Objective:
Our objective in this machine learning project is to examine the specific characteristics of each reservation and predict which reservation will lead to the purchase of these vouchers.

### Why?
Restaurant voucher sales are of strategic importance because:
* It helps to reduce the no-show rate of reservations
* It encourages users to try out new restaurants that they otherwise might not try- introducing a discovery utility to the platform
* It increases user satisfaction by offering them a good deal and potentially expands their lifetime value

### General workflow:
Because this is a raw dataset, there are additional steps to prepare the data to make sure it is readable to the code libraries that I will be using. A large proportion of time was actually spent on cleaning and parsing the data, but none of this processing will be shown on the notebooks in this project.
1. Parsing and cleaning the data to make sure it is readable and compatible with the code
2. Split data into training and testing sets
3. Resample the dataset to combat the class imbalances
4. Apply data to classification prediction models and machine learning tools
5. Optimise model's precision/ recall by fine tuning parameters

### Models to apply:
* Logistic regression
* XGboost

### Some assumptions and limitations
* I’m assuming that the vouchers are going to be bought together with or after the reservation is made for simplicity's sake
* Since this is a real world dataset, there is also a good chance that there might not be enough telling features present in the dataset to generate a good classification model. If this is the case, it can be seen directly from the results of the model itself.