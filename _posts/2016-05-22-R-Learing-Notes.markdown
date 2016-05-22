---
layout: post
title: R Learning Notes #1
---
	
R Learning Notes #1
===================

	duplicated(x, incomparables = FALSE, ...)

### 寻找是否有重复元素，并返回逻辑向量

	which.min(x)
	which.max(x)
	
### 寻找寻找向量中最小/最大元素的位置，自动忽略NA

	library(impute)
	impute(x, what = c("median", "mean"))

	
### 将矩阵或数据框中的NA用该列的中位数或平均数代替	

	impute.knn

### 将矩阵或数据框中的NA用该列k最近邻域平均数代替