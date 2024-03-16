# Table of Contents (up to date)
- [Table of Contents (up to date)](#table-of-contents-up-to-date)
- [Programming](#programming)
  - [Python](#python)
    - [Scrapy](#scrapy)
    - [Geospatial analysis](#geospatial-analysis)
- [Statistics](#statistics)
  - [Realiability and validity tests for questionnaires](#realiability-and-validity-tests-for-questionnaires)
  - [Sensitivity analysis](#sensitivity-analysis)
    - [A bimodal scoring](#a-bimodal-scoring)
- [Spatial analysis](#spatial-analysis)
  - [Multivariate clustering algorithm](#multivariate-clustering-algorithm)
  - [Conditional autoregression model (CVR)](#conditional-autoregression-model-cvr)
  - [Spatial and temporal non-stationarity](#spatial-and-temporal-non-stationarity)
    - [Geographically Weighted Regression (GWR)](#geographically-weighted-regression-gwr)
    - [Geographically and temporally weighted regression (GTWR)](#geographically-and-temporally-weighted-regression-gtwr)
    - [Multiscale geographically weighted regression (MGWR)](#multiscale-geographically-weighted-regression-mgwr)
- [Regression](#regression)
  - [Covariate in regression analysis](#covariate-in-regression-analysis)
  - [Logistic regression](#logistic-regression)
    - [Odds ratio (OR) and Relative risk (RR)](#odds-ratio-or-and-relative-risk-rr)
    - [Multinomial logistic regression](#multinomial-logistic-regression)
    - [Ordinal logistic regression](#ordinal-logistic-regression)
    - [Interactions with Logistic Regression](#interactions-with-logistic-regression)
- [Environmental models](#environmental-models)
  - [InMAP（Intervention Model for Air Pollution）](#inmapintervention-model-for-air-pollution)

# Programming
## Python
### Scrapy
- [Scrapy 2.5 documentation](https://www.osgeo.cn/scrapy/index.html)

### Geospatial analysis
-[Working with raster data](https://kodu.ut.ee/~kmoch/geopython2020/L5/raster.html)

# Statistics
## Realiability and validity tests for questionnaires
1. [spss数据分析--信度效度分析](https://www.zhihu.com/tardis/zm/art/270005975?source_id=1003)
2. [简单实用！一文掌握效度分析所有知识点！](https://zhuanlan.zhihu.com/p/182577757)
3. [调查问卷的信度分析和效度分析](https://zhuanlan.zhihu.com/p/350171180)

## Sensitivity analysis
### A bimodal scoring
- [Tutorial]??

# Spatial analysis
## Multivariate clustering algorithm
1. [Multivariate Clustering (Spatial Statistics)](https://pro.arcgis.com/en/pro-app/latest/tool-reference/spatial-statistics/multivariate-clustering.htm)
2. [How Multivariate Clustering works](https://pro.arcgis.com/en/pro-app/latest/tool-reference/spatial-statistics/how-multivariate-clustering-works.htm#:~:text=The%20Multivariate%20Clustering%20tool%20uses,is%20employed%20to%20cluster%20features.)

## Conditional autoregression model (CVR)
- [Tutorial using python](https://www.pymc.io/projects/examples/en/latest/case_studies/conditional_autoregressive_priors.html)

## Spatial and temporal non-stationarity
### Geographically Weighted Regression (GWR)
- [Original paper](https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/1467-9884.00145)
- [Algorithm using Python](https://pypi.org/project/mgtwr/)

### Geographically and temporally weighted regression (GTWR)
- [Original paper](https://www.tandfonline.com/doi/full/10.1080/13658810802672469)
- [Additional paper](https://onlinelibrary.wiley.com/doi/full/10.1111/gean.12071)
- [Algorithm using Python](https://pypi.org/project/mgtwr/)

### Multiscale geographically weighted regression (MGWR)
- [Original paper](https://www.tandfonline.com/doi/full/10.1080/24694452.2017.1352480)
- Algorithms: [Official Python codes](https://pypi.org/project/mgwr/), [Third-party Python codes](https://pypi.org/project/mgtwr/), [Official Software](https://sgsup.asu.edu/sparc/multiscale-gwr)

# Regression
## Covariate in regression analysis
1. [论文中出现的“Covariates”协变量怎么去理解？](https://zhuanlan.zhihu.com/p/603381875)
简单来讲，协变量指影响解释变量和响应变量之间反应关系，但不是我们所关心的变量，如社会人口统计学特征（性别，年龄等）。<br>
这种协变量导致的影响大致分类四类：<br>
（1）混杂效应<br>
（2）噪音污染<br>
（3）修饰/交互作用（interaction term）<br>
（4）中介作用（moderation term）<br>
一般来讲，回归分析可以解决协变量带来的混杂效应和噪音污染的影响，但无法消除interaction term和moderation term的作用。<br>

## Logistic regression
### Odds ratio (OR) and Relative risk (RR)
- Shelly’s 课程：Lecture 6 Disease frequencies and measures of association
### Multinomial logistic regression
- [【Stata小课堂】第25讲：无序多分类Logistic回归(Multinomial Logistic Regression)](https://www.youtube.com/watch?v=4wuzUR2v6yQ)
### Ordinal logistic regression
- [The most useful tutotialL: Module 5 - Ordinal Regression](https://www.restore.ac.uk/srme/www/fac/soc/wie/research-new/srme/modules/mod5/index.html)
- [How to choose link function?](https://bookdown.org/chua/ber642_advanced_regression/ordinal-logistic-regression.html#link-function): The link function is depended on the cumulative probability function of outcome variable.
- [How can i adjust parameters in logistic regression?](https://www.researchgate.net/post/How-can-i-adjust-parameters-in-logistic-regression)
- [因变量有序多分类资料的logistic回归：SPSS操作与回归系数的解释](https://www.plob.org/article/23786.html)
- [【Stata小课堂】第24讲：有序多分类Logistic回归(Ordinal Logistic Regression)](https://www.youtube.com/watch?v=u3jl8wJCOfM)
- [SPSS官方文档](https://www.ibm.com/docs/zh/spss-statistics/25.0.0?topic=model-choosing-predictors-location#plum_germcr_choose_location)
### Interactions with Logistic Regression
- [Interactions with Logistic Regression](https://web.pdx.edu/~newsomj/cdaclass/ho_interactions.pdf)
- [Logistic Regression: Interaction Terms](https://www.cantab.net/users/filimon/cursoFCDEF/will/logistic_interact.pdf)

# Environmental models
## InMAP（Intervention Model for Air Pollution）
- [Introduction](https://inmap.run/) 


