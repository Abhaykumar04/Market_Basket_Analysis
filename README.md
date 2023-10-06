# Market_Basket_Analysis

# Market Basket Analysis (MBA) Case Study
![image](https://github.com/Abhaykumar04/Market_Basket_Analysis/assets/112232080/a139f8e6-ce52-4d1e-8935-6e34b40d527c)

## Problem Statement
Within the context of this analysis, we are exclusively examining the purchasing behavior of two specific items - Bread and Butter. Our primary objective is to ascertain whether there exists compelling evidence to indicate that the acquisition of Bread is causally linked to the purchase of Butter.

**Hypothesis:** We hypothesize that there exists significant evidence to substantiate the assertion that the purchase of Bread leads to the purchase of Butter.

## Dataset
The dataset underpinning this investigation is publicly available on Kaggle, encompassing transactional data originating from an establishment named "The Bread Basket." The dataset's temporal scope spans from October 30, 2016, to April 9, 2017, providing comprehensive insights into the items retailed by the bakery. Noteworthy inclusions in the product portfolio of "The Bread Basket" encompass coffee, bread, muffins, cookies, and other bakery items. Situated in the heart of Edinburgh, this bakery holds historical significance.

## Interpretation and Implications
The ensuing analysis yields a series of compelling insights into item associations within the bakery's transactional records. Key findings and implications include:

- The top 10 itemsets have been meticulously sorted by confidence value. Notably, each of these itemsets boasts a support value exceeding 1% and a lift value surpassing 1.

- The foremost itemset serves as a concrete example of an association rule: "if Toast, then Coffee." This association boasts a support value of 0.023666, signifying that approximately 2.4% of all transactions involve the concurrent purchase of Toast and Coffee. Furthermore, a confidence level of 70% suggests that Coffee sales frequently coincide with the purchase of Toast. The lift value, which stands at 1.47 (exceeding 1), signifies that the acquisition of Coffee is significantly influenced by the purchase of Toast, as opposed to Coffee's purchase occurring independently of Toast. This lift value of 1.47 implies that the acquisition of Toast elevates the likelihood of acquiring Coffee by a factor of 1.47.

In light of these insights, we draw the following conclusion: there is compelling evidence to suggest that the purchase of Toast is strongly associated with the purchase of Coffee. To leverage this insight, the proprietor of "The Bread Basket" bakery may contemplate the bundling of Toast and Coffee as a cohesive Breakfast Set or Lunch Set. Moreover, staff within the establishment could receive training in the art of cross-selling, with a focus on encouraging Coffee purchases among patrons who opt for Toast, recognizing that these items exhibit a strong tendency to be acquired in tandem. Implementation of such strategies has the potential to significantly augment the bakery's revenue stream.
