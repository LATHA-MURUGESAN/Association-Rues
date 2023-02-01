# Association-Rues
Association rules are a set of techniques used in data mining and machine learning 
to uncover relationships between items in large datasets. 
The goal of association rule learning is to find associations between variables in a database 
that can be used to predict the presence of an item based on the presence of other items.

Support: Support is a measure of how frequently an item set appears in a data set. 
It is calculated as the number of transactions that contain the item set divided by the total number of transactions.
High support indicates that the item set is frequently purchased, while low support indicates that the item set is infrequently purchased.

Confidence: Confidence is a measure of the degree to which the presence of the antecedent item set leads to the presence of the consequent item set. 
It is calculated as the support of the item set A∪B divided by the support of the antecedent item set A. 
High confidence indicates a strong association between the antecedent and consequent item sets, while low confidence indicates a weak association.

Lift: Lift is a measure of the strength of the association between the antecedent and consequent item sets, 
compared to the expected strength of the association if the two item sets were independent.
Lift is calculated as the ratio of the confidence of the rule if A then B divided by the support of the consequent item set B.
Lift greater than 1 indicates that the item sets are more strongly associated than expected, 
while lift less than 1 indicates that the item sets are less strongly associated than expected.
