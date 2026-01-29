# Assignment17_1

**Notebook Path:**

https://github.com/kapilsharma2411/Assignment17_1/blob/d97dbf14f674609a07f4864b46f07f17d0a5ab99/Assignment_17-1.ipynb

**Dataset Path :**

https://archive.ics.uci.edu/ml/datasets/bank+marketing

**Summary :**

This project was to explore above datset and develop models to predict term deposit subscriptions for the customers that were contacted during current/past campaigns run by Bank Marketing Team. We compared various models like : 

 - Logistic Regression
 - KNN
 - Decision Trees
 - SVM

 After assessing the baseline scores for all of the above models, we went ahead and tuned these models so we can have high accuracy and F1 scores for the predictions. Logistic Regression seemed to be the best fit model for the above objective. 

## Below are the Business Outcomes & Recommendations : 

### 1. Smarter Campaign Training
**Prediction:**

The model can rank customers by likelihood of subscription.

**Decision:**

 - Target only the top 20–30% highest-scoring customers

 - Avoid blanket calling strategies

**Business Impact:**

 - Fewer calls

 - Higher conversion rate

 - Reduced customer annoyance

### 2. Improved Marketing ROI
**Insight:**

Accuracy alone is misleading; F1-score optimization significantly reduces wasted calls.

**Decision:**

 - Optimize campaigns using probability thresholds instead of default 0.5

 - Adjust threshold depending on campaign cost and revenue goals

**Business Impact:**

 - Lower cost per successful subscription

 - Higher campaign profitability

### 3. Agent Productivity Optimization

**Insight:**

Model predictions allow prioritization of leads.

**Decision:**

 - Assign high-probability customers to senior agents

 - Automate or deprioritize low-probability segments

**Business Impact:**

 - Better agent utilization

 - Increased subscriptions per agent