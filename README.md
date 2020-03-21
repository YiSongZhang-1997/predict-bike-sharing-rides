# 预测共享单车使用情况 —— Udacity Project

## 项目简介
创建一个神经网络模型来预测每日共享单车的使用情况。

## 数据来源
https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

## 文件说明

### Your_first_neural_network.ipynb
记录了神经网络的建模流程和预测结果

### hour.csv
数据集文件
按照每小时汇总的共享自行车使用人数。记录数：17379 小时

	- instant：记录索引
	- dteday：日期
	- season：季节（1：春季，2：夏季，3：秋季，4：冬季）
	- yr : 年份（0：2011 年，1：2012 年）
	- mnth：月份（1 到12 月）
	- hr : 小时（0 到 23 时）
	- holiday: 当天是否是假期（数据来自 http://dchr.dc.gov/page/holiday-schedule）
	- weekday: 星期几
	- workingday: 如果不是周末或假期则是 1 ，否则是 0。
	+ weathersit : 
		- 1: 晴朗、飘着几朵云、局部多云
		- 2: 薄雾加多云、薄雾加碎云、薄雾加几朵云、薄雾
		- 3: 小雪、小雨加雷暴加散云、小雨加散云
		- 4: 大雨加冰雹加雷暴加薄雾、下雪加雾
	- temp: 标准化温度（摄氏度）。标准化后的值为原数据除以41（最大值）
	- atemp: 标准化体感温度（摄氏度）。标准化后的值为原数据除以50（最大值）
	- hum: 标准化湿度。标准化后的值为原数据除以100（最大值）
	- windspeed: 标准化风速。标准化后的值为原数据除以67（最大值）
	- casual: 临时用户数
	- registered: 注册用户数
	- cnt: 租赁自行车总用户数（包括临时用户和注册用户）


[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}

