<h1>Students Performance Challenge - A Kaggle Dataset</h1>

<h2>Goals</h2>
This repository is for learning. I used Kaggle's Student Performance dataset to evaluate good performance and predict it.

<h2>The Dataset</h2>
The dataset itself is described on Student_performance.ipynb. But, we are dealing with unbalanced data which are both categorical an numerical. After some research we have basically 2 target features, one is categorical and trivial (GradeClass) and the other one is numerical and not that much obvious (GPA).

GPA is a metric that also measures student performance but in a different way. If we use it on a classifiar it will mostly give us a good accuracy because both measure basically the same thing. So we can drop it or...

<h2>Results</h2>
On our EDA we found something interesting: some numerical features had high correlation with GPA, so i tried making an classifier using all data from dataset and a regressor using only numerical data. The founding was very interesting. XGBoost with hyperparameters optimized had near 75% accuracy while Linear Regressor gave us a 0.8776 Rˆ2.

It was very interesting working in this notebook and im very open to debate and to learn more. Dont hesitate to inbox my!
Thank you
