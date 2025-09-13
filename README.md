Hello!

This is a sci-kit learn project aiming to identify what demographic traits in adults are good predictors for whether that person makes less or more than 50K (USD) in income annually. This report can be found by simply navigating to "sklearn-ML.ipynb".

The results of this report were quite interesting. Factors related to life/relationship/career progression—such as age, marital status, and occupation—were the most reliable metrics for predicting whether someone made more or less than 50K a year. However, innate characteristics such as race and sex had very little ability to determine which income group someone belonged to.

This means that intrinsic, unchangeable qualities weren't all that influential to success. The most important factors were seniority, marital status, age, and occupation, which by far outweighed other metrics.

In terms of impact, this report has interesting ramifications. A major consideration often discussed is whether intrinsic qualities such as race and sex are major predictors of future economic success. However, this report brings the good news that economic predetermination through unchangeable qualities (especially race and sex) may not be that strong.

It is important to note a couple of limitations. The scope of this project means that we don't know whether high-importance characteristics like age have a positive or negative correlation with income—we’ll need another separate analysis to find out. This project also lacks granularity, since we use the very broad categories of ">50K income" and "<=50K income." Although this doesn’t affect importance weight much, it does limit detail.

Another consideration is that, due to a lack of data volume for people who make more than 50K annually, the ML model has some trouble correctly sorting that group. This imbalance may slightly affect the importance weights as well.