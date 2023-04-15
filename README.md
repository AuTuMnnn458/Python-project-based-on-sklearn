# Python-project-based-on-sklearn
本项目主要研究在sklearn库下实现机器学习算法。算法包括：线性回归，岭回归，逻辑回归，决策树模型等。

本项目基于jupyter notebook，与我的另一个库 (https://github.com/AuTuMnnn458/Python-project-based-on-Numpy-and-Pandas) 相对应，这里并不会展开详细讨论算法的原理，参数讨论，模型的变种等等，主要专注于调用sklearn库实现快速建模，以及对简单例子的应用，包括训练预测和可视化。
 
## 1.线性回归
调用sklearn库中的LinearRegression与Ridge类，使用线性回归和岭回归的模型。对于boston housing数据集中的数据进行回归分析。

## 2.逻辑回归
调用LogisticRegression类进行单分类和多分类。注意逻辑回归是一个分类方法。

## 3.决策树
用sklearn.tree中的DecisionTreeClassifier和DecisionTreeRegressor进行分类和回归。分类使用Iris数据集，回归使用Boston housing数据集。分类决策树中，输出结果是叶子节点的众数；而回归决策树中，改用叶子节点的平均数作为结果。可视化使用sklearn的tree中tree.plot_tree(比graphviz要方便).
