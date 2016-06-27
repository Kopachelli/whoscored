# whoscored

1. whoscored.com crawling to csv
- https://github.com/radajin/whoscored/blob/master/crawling/crawling_whoscored.ipynb

2. csv migration to mysql db

3. predict rating - regression each postion
- https://github.com/radajin/whoscored/blob/master/predict_rating/forword_ols.ipynb
- https://github.com/radajin/whoscored/blob/master/predict_rating/goalkeeper_ols.ipynb
- get data from mysql db (mins > 270)
- scaling
- OLS and remove some feature (check t-value)
- anova table and remove some feature (check F)
- predict rating from some players features
   
4. recomend position - dicision tree entropy
- get data from mysql db (single position players)
- make model (dicision tree(entropy), naive baysian)
- decide model : dicision tree
- check confusion matrix & classification report
- recomend one postion multy positon players
