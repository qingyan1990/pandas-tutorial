Pandas主要用于处理下面的三种数据结构:
* Series
* DataFrame
* Panel

这些数据结构都是构建在Numpy array的基础上
### 简要描述
DataFrame是Series的容器，而Panel是DataFrame的容器。
|Data Structure|Dimensions|Description|
|:-|:-:|:-|
| Series | 1 | 1维同构数组，大小不可更改 |
| DataFrame | 2 | 二维数据，大小可以更改，可以存储异构数据 |
| Panel | 3 | 三维数据，大小不可以更改 |
#### 可更改性
Pandas中的三种数据结构都是值可更改的,同时也只有Series是大小不可更改。  
DataFrame和Series较为重要，而Panel则很少使用。
### DataFrame
#### 关键点
* 异构数据
* 大小可更改
* 值可更改
#### 示例

|Name|Age|Gender|Rating|
|:-|:-:|:-:|-:|
| Steve | 32 | Male |	3.45 |
| Lia | 28 | Female |	4.6 |
| Vin | 45 | Male	| 3.9 |
| Katie | 38 | Female | 2.78 |
DataFrame可以看做是一张表格，每一列代表一个属性，每一行代表一条记录。  
其中每一列或者每个属性都有自己对应的数据类型
|Column|Type|
|:-|:-|
| Name | String |
| Age | Integer |
| Gender | String |
| Rating	| Float |
