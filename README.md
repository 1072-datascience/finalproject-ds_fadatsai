# < Title of your final project >

### Groups
* < 張璟榮, 104302033 >
* < 莊凱鈞, 104703027 >
* < 郭芷瑄, 104703040 >
* < 陳海坤, 107753024 >
* < 黃清昱, 104753032 >

### Goal
Our goal is to estimate the HDI Human Development of the cities in Brazil.

### Demo 
You should provide an example commend to reproduce your result
```R
Rscript code/your_script.R --input data/training --output results/performance.tsv
```
* any on-line visualization

## Folder organization and its related information

### docs
* Your presentation, 1072_datascience_FP_<yourID|groupName>.ppt/pptx/pdf, by **Jun. 25**

### data

* Source: (https://www.kaggle.com/crisparada/brazilian-cities?fbclid=IwAR2aoN1eihNzzmywq9z_NQpBHbC6Igy5nmQNgmFNp-wEAlG3odMfpqmB0Tk "A collection of 79 attributes from Brazilian Cities")
* Input format
  * .csv
* Any preprocessing?
  * Handle missing data
  整個row刪除: IDHM、經緯度
  平均值填補:IBGE_DU、IBGE_DU_Pro、Pr_Assets、Pu_Assets、Cars、Motorcycles、Wheeled_tractor、MUN_EXPENDIT
  以0填補: HOTELS、BEDS、Pr_Agencies、Pu_Agencies、Pr_Bank、Pu_Bank、MAC、Wal-Mart、Post_offices
  * Scale value

### code

* Which method do you use?
linear regression、logistic regression、decision tree、random forest、BaggingRegressor、KNN
* What is a null model for comparison?
25%

* How do your perform evaluation? ie. Cross-validation, or extra separated data
train_test_split

### results

* Which metric do you use
** accuracy
* precision, recall, R-square
** R-square
* Is your improvement significant?
** Yes
* What is the challenge part of your project?
** preprocessing、domain knowledge insufficient

## Reference
* Code/implementation which you include/reference (__You should indicate in your presentation if you use code for others. Otherwise, cheating will result in 0 score for final project.__)
*(https://www.kaggle.com/crisparada/brazilian-cities-a-simple-exploration)
* Packages you use: pandas, matplotlib, numpy, seaborn, scipy, math, os, sklearn


