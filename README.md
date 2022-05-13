# market_basket_analysis
Market basket analysis is an association analysis method used to identify an association between different itemset then find frequent patterns in a database, D.<br>
Support is the percentage of transactions in D that contains A union B, P(A u B).<br>
Confidence is the percentage of transactions in D that containing A that also contains B, P(A|B).<br>
Rules that are considered strong, are those that satisfy both a minimum support(min sup) and a minimum confidence(min conf).<br>
Different algorithms used in market basket analysis are apriori, FP growth, SETM, AIS. For this particular analysis, we will be using the Apriori algorithm.<br>
Steps involved in working with Apriori algorithm:<br>
-Define the min sup and min conf<br>
-Find all subsets in the database with higher support than the min sup<br>
-Find all rules for thtse subsets with higher confidence than min conf<br>
-Sort these association rules in decreasing order<br>
-Analyze these rules along with their support and confidence<br>

A store dataset readily available on Kaggle will be used for this analysis
