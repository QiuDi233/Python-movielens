# Python-movielens
Python程序设计与数据科学导论期中大作业：基于观影数据集的数据分析与挖掘  

### Task1：在movielens 1M的数据集上，统计分析观影的性别偏好。
´ 需要完成：

´ 综合观影信息、评分信息，设计合理方案分别筛选出前20部比较流行的（rating > 300）男性/
女性 偏好电影。

´ 针对不同类型的电影（genres），统计分析男/女偏好程度（需要做归一化），通过双色直方图
对比显示。
### Task2：在movielens 1M的数据集上，通过观影及评分信息，预测观众的年龄-性别
´ 需要完成：

´ 拆分训练集-测试集（20%评测），实现评测方案（准确率-召回率）

´ 实现分类器模型，对观影数超过100的用户进行预测。调整模型及参数。包括并不限于特征降维
来获得较好的效果。（提示：在用户年龄预测问题中，由于年龄段本身是具有序关系的。常规的模型优化方法不
一定会有明显的效果， 有兴趣的同学可以看一下ordinal regression模型。有余力可以尝试，不算分。）

### Task3：在movielens 1M的数据集上，通过观影-评分及电影简介等信息，对观影>100的用户实现用户画像。

´ 包括且不限于：最喜欢-最不喜欢的电影类型。输出3-5部代表性的电影反映该用户的观影
偏好。（可以通过对偏好的电影集合运用图分析技术或SVD分解来实现）

´ ⾃定义⼀些合理的类型概 念，如，家庭主妇最爱，烧脑神剧等，对用户进行标签标记。
或者综合电影风格，生成用户观影偏好的雷达图。生成用户偏好词云等。
