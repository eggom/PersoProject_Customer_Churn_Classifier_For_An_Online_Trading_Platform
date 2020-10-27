# Customer Churn Analysis and Predictor for an online trading platform (Classification ML)

### Abstract:
This notebook summarises an ML model to predict customer churn over Internet online trading Platforms, providing a grade on the risk of leaving the platform.


### A bit of background in online trading platforms:
It can be recognized that, throughout the last few years, there´s been an spike on the interest of "usual" consumers to enrol onto online trading platforms to perform daily/weekly operations over FOREX and other financial markets.

As a result there has been an strong penetration on the ecosystem of online trading brokers (or platforms) to help fulfill those needs to the customers.

Being many users out there for online trading portals mean that there is an increased interest from those companies to understand their customer profiling and run some analytics over their customer pool to predict churn based on user activity on the platform.

Keeping customers happy so they do not move their investments elsewhere is key to maintaining profitability.


### What is this project about:
I have based this project over a Jupyter notebook where the scikit-learn library is being used to predict classes. scikit-learn provides implementations of many classification algorithms. In here, we have chosen the random forest classification algorithm to walk through all the different steps.


### Data Catalogue

The predicting features input is a collection of attributes from the platform user such as customer ID, age, total units traded, days since last login etc. The target feature is the churn risk that has been coded as:
* High
* Medium
* Low

### Ultimate Goal

The ultimate goal of the project is the deployment of a model to classify whether a given customer’s probability of churn will be high, medium, or low.
