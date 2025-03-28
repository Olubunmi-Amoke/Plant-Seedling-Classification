# Plant-Seedling-Classification

## Problem Statement
#### Context
In recent times, the field of agriculture has been in urgent need of modernizing, since the amount of manual work people need to put in to check if plants are growing correctly is still highly extensive. Despite several advances in agricultural technology, people working in the agricultural industry still need to have the ability to sort and recognize different plants and weeds, which takes a lot of time and effort in the long term. The potential is ripe for this trillion-dollar industry to be greatly impacted by technological innovations that cut down on the requirement for manual labor, and this is where Artificial Intelligence can actually benefit the workers in this field, as the time and energy required to identify plant seedlings will be greatly shortened by the use of AI and Deep Learning. The ability to do so far more efficiently and even more effectively than experienced manual labor, could lead to better crop yields, the freeing up of human inolvement for higher-order agricultural decision making, and in the long term will result in more sustainable environmental practices in agriculture as well.
The aim of this project is to Build a Convolutional Neural Network to classify plant seedlings into their respective categories.

#### Data Dictionary
**List of Species**:
- Black-grass
- Charlock
- Cleavers
- Common Chickweed
- Common Wheat
- Fat Hen
- Loose Silky-bent
- Maize
- Scentless Mayweed
- Shepherds Purse
- Small-flowered Cranesbill
- Sugar beet

#### Insights and Recommendations

Both models' performances indicate underfitting. Adding more convolutional layers or increasing the number of filters in existing layers to extract richer features might be helpful towards improving the models.

The second model performed better than the first, with approximately 78% test accuracy - about 6% better than the first model.

Despite the ~78% test accuracy, the model can already automate significant portions of the manual classification task, saving time and reducing human errors.

Prioritizing on improving accuracy for critical classes by identifying which plant categories are most misclassified and assessing their economic or agricultural importance.
