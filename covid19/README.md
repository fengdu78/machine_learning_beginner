# 新冠肺炎的可视化和预测分析

新冠肺炎现在情况怎么样了？推荐一份jupyter notebook代码进行了分析，把数据可视化，并对感染人数进行了预测。
数据更新到2020-4-14。

本文的可视化通过ployly实现。

本文数据更新到4月14日，最新数据下载：

https://www.kaggle.com/corochann/covid-19-eda-with-recent-update-on-april/data?scriptVersionId=32149572

（下载train.csv、test.csv、usa_states2.csv） 到input的convid19目录即可，数据更新到2020-4-14。

原始数据是这里下载修改的：

https://github.com/CSSEGISandData/COVID-19

这份分析代码主要分为以下几个部分：
- 全球趋势
- 国家（地区）增长
- 省份情况
- 放大美国：现在美国正在发生什么？
- 欧洲
- 亚洲
- 现在哪个国家正在复苏？
- 什么时候会收敛？通过S型拟合进行预测