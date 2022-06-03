# Data-Science-Apriori

What Is Association Rule Mining?
-------------------------------
As mentioned before, the Apriori algorithm is used for the purpose of association rule mining. Now, what is association rule mining? Association rule mining is a technique to identify frequent patterns and associations among a set of items.

For example, understanding customer buying habits. By finding correlations and associations between different items that customers place in their ‘shopping basket,’ recurring patterns can be derived. Say, Joshua goes to buy a bottle of wine from the supermarket. He also grabs a couple of chips as well. The manager there analyses that, not only Joshua, people often tend to buy wine and chips together. After finding out the pattern, the manager starts to arrange these items together and notices an increase in sales.

This process of identifying an association between products/items is called association rule mining. To implement association rule mining, many algorithms have been developed. Apriori algorithm is one of the most popular and arguably the most efficient algorithms among them. Let us discuss what an Apriori algorithm is.
Apriori algorithm assumes that any subset of a frequent itemset must be frequent.

Concepts of Apriori
------------------
Support
-------
Fraction of transactions that contain an itemset.
For example, the support of item I is defined as the number of transactions containing I divided by the total number of transactions.

Confidence
----------
Measures how often items in Y appear in transactions that contain X
Confidence is the likelihood that item Y is also bought if item X is bought. It’s calculated as the number of transactions containing X and Y divided by the number of transactions containing X.

Frequent Item Set
An itemset whose support is greater than or equal to a minSup threshold
Frequent itemsets or also known as frequent pattern simply means all the itemsets that the support satisfies the minimum support threshold.
