> 使用说明：
1. 使`data_?.csv`与`finetune.ipynb`在同一目录下
2. 下载finetune.ipynb，在finetune.ipynb中调整参数
3. 将参数调整后的finetune.ipynb|结果, 上传

##仅使用studentInfo和课程概要信息①
1. 结果(未调参)
Decision Tree -----> 0.6601446849182575
Random Forest -----> 0.6865841467943267
Logistic Regression -----> 0.6906667372009867
ExtraTree -----> 0.6872335189517572
Xgboost -----> 0.6924285716192883
Catboost -----> 0.6945626042036639
2. [数据下载](http://49.235.211.79/data/data_1.csv)

##使用studentInfo和课程概要信息以及前1/4的VLE信息②
1. 结果(未调参)
Decision Tree -----> 0.4653454460838124
Random Forest -----> 0.718918138744208
Logistic Regression -----> 0.7066712609133498
ExtraTree -----> 0.7064850005321951
Xgboost -----> 0.7181290389364434
Catboost -----> 0.7158563332566701
2. [数据下载](http://49.235.211.79/data/data_2.csv)



