# education-ml

For this machine learning project, our group downloaded multiple years of [College Scorecard Data](https://collegescorecard.ed.gov/data/) to predict student outcomes based off university factors such as acceptance rate, completion rate, transfer rate, size, cost, etc.

Using seaborn.scatterplot to find initial relationships, we concluded that private universities tend to be more expensive and have fewer students.  Below is the plot of enrollment size vs cost and school type (private or public).
<img src="https://github.com/MissWibbon/education-ml/blob/data_cleaning/images/CostSizeTypeScatter.JPG" width="400">

To find more correlations that may not be as obvious, we ran multiple importance classifiers including Random Forest, gradient boosting, and permutation.  Average Cost was the greatest importance across all models.  
<img src="https://github.com/MissWibbon/education-ml/blob/data_cleaning/images/GradientBoostingImportance.JPG" width="400">



**Technologies and Tools Used:** Python, Pandas, Matplotlib, numpy, seaborn, Random Forest, sklearn, Tableau

**Contributors:** [Kelsey Oros](https://github.com/kelseyoros), [Gracie Xia](https://github.com/GracieX), [Michelle Wuebben](https://github.com/MissWibbon), [Joon Chang](https://github.com/joonc3779), [Graham Livingston](https://github.com/gramlivingston)