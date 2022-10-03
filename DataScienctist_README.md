# Apriori in the Cart: To Buy or Not?


## Objective:
In this study, we try to implement the Apriori algorithm on an e-commerce electronics store dataset which consists of user-session data. The objective is to find uncommon / out-of-the-box association rules between specific electronic products with the intent to boost sales of these products by explicitly promoting them together.

Link to our Medium article on this study:

## Dataset Links:
- [E-commerce Electronics Store Dataset](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)
- [Grocery Store Dataset](https://www.kaggle.com/datasets/ahmtcnbs/datasets-for-appiori)

## Conclusion:
We concluded that the Apriori algorithm is not applicable for all kinds of datasets. It is suitable where there is a high chance of multiple products being purchased together, for example, in grocery stores or sports equipment stores or departmental stores, etcetera. Since electronics are very high-priced items there are very few transactions where multiple products are frequently purchased together. Therefore, in such cases, Apriori is not useful for finding significant association rules.

Moreover, even where Apriori is applicable, the most important metric to consider is support because a high support value indicates a high number of transactions for a given combination of products. Then, if the lift value is greater than 1, we can conclude that the association rule is significant, and we can explore that further for greater revenue generation.

## References:
- https://github.com/ashishpatel26/Market-Basket-Analysis
- https://www.youtube.com/watch?v=guVvtZ7ZClw&t=478s
