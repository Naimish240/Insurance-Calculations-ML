# Insurance-Calculations-ML

[Kaggle Notebook](https://www.kaggle.com/naimish123/insurance-calculations)

The issue of missing packages has plagued the postal and shipping industry for as long as one can remember. This is especially costly (in terms of both money and reputation) in the modern day and age, where e commerce companies regularly ship out valuable goods to their paying customers.

Through the course of this notebook, I intend to showcase the potential for using logistic regression to save costs in an e commerce company by building a model to identify the parcels to apply for insurance for.

In this Hypothetical example, we managed to save $457253.78 in insurance costs for 22,581 parcels.

**Note**:
1. Insurance rates have been defined as insurance_cost = max($20, 10% the cost of the order) for this example.

2. We are assuming that a random 5% of all parcels get stolen. Hence, we calibrate the model to account for this unbalance.

3. Total reveune generated from the 22,581 parcels stands at $6531261.43
