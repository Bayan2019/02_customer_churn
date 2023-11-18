# 02_customer_churn

In the notebook `02_customer.ipynb` there is analysis of customer churn rate of Bank. The additional visualization and overall summary can be found [here](https://bayan2019.github.io/03_fedex_html/)

Customer churn in banking is when a customer closes their account and switches to another bank. Over their customer lifetime, customers generate fees on transactions, banking fees, credit cards, home loans, and personal loans. Churn is a problem, because the bank loses revenue, and it costs more to acquire a new customer than retaining an existing one.

Objective(s): Minimize the customer churn.

Constraints: Maximize revenue from existing customer and quality of bank services.

Success Criteria:

- Business Success Criteria: understanding what keeps customers engaged is extremely valuable knowledge, as it can help you to develop your retention strategies. Reduce retention by 20%-30%

- Economic Success Criteria: bank can save 20% on marketing budget to acquire new customers.

Proposed Plan:
Classification of customer churn will allow to understand the characteristics of each group.

There was provided a dataset or 10 000 package delivery records.

Actions performed:

- Performed typecasting -- converted some variables from 'float' to 'integers'
- Performed Exploratory Data Analysis which can be briefly considered here https://bayan2019.github.io/03_fedex_html/index.html
- Carried out normality check for numerical variables (they all do not have normal distribution)
- Scaled numerical features.
- Conducted One-hot encoding.
- Build 6 models -- K Nearest Neighbors, Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, and MLP.
- After evaluation of 6, we discovered that all, except Decision Tree, performed same way.