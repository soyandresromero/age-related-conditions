![Static Badge](https://img.shields.io/badge/Language-Python-blue?logo=python) ![Static Badge](https://img.shields.io/badge/Language-Jupyter-blue?logo=Jupyter) 


# ICR - Identifying Age-Related Conditions

The goal of the competition was according to its own description: predict if a person has any of 3 medical conditions. Further details of the competition are available in Kaggle: [ICR](https://www.kaggle.com/competitions/icr-identify-age-related-conditions).

My best solution was achieved wiht a LightGBM Model with a simple cross-validation method to optimize the classification score.

In the [Jupyter Notebook](https://github.com/soyandresromero/age-related-conditions/blob/51aa50311a0fff92eb46be08a1ee480c9eb606b2/ICR_Final_V2.ipynb) is described in detail all the process followed to achieve the results granting me my first Bronze Medal in Kaggle. On it, I was able to perform:
- Exploratory Data Analysis: with Imputations of missing values.
- As the competition score was based on a special case of a *Log-Loss*, an analysis to understand how it works was also made.
- 3 Machine Learning Methods were trained with Cross-Validation to perform hyper parameter tuning and then their results were compared in terms of the Loss Function and the Confusion Matrices obtained for each case.
- Done that, the prediction was made using the best result among them.

