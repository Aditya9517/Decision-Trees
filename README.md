# Decision-Trees
A decision tree with binary splits for classification

- The accuracy was found to be 96.72%
- They were two misclassifications - classification accuracy can be caluclated as 59/61 (total records) * 100.

Conclusion:

- Based on the values of the ingredients for the recipe, we can conclude that if a recipe has certain values of ingredients, it can be classified as a cupcake or a muffin.
- If sugar <= 19, egg <= 12, butter/margarine <= 18 & baking_powder <= 2 or cinnamon > 11, it is a muffin.
- If sugar > 19 & vanilla > 6 & pumpkin/fruit > 26, it is a muffin.
- In all other cases, it is a cupcake.
- We can evidently observe this from the aforementioned code section of the decision tree.
