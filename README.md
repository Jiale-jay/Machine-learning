# Machine-learning (Neural Networks and Image Classification)
This is a collection of machine learning projects.
The content contains several tasks

Task 1
Classifier training on MNIST using a self-constructed network.

Task 2
Predicting the Boston house price dataset (built-in Sklearn data) using a self-built network.

Task 3
The third task was given a fraud detection dataset from the Texas A&M International University Dataverse.
The dataset itself has been PCA-dimensionally reduced and is basically impossible to understand visually, so we use this data for pure neural network classifier training. Attempts were made to train the classifier to over 70% accuracy.

Tips:
1. MNIST classifier here if you want to further improve the accuracy, you can consider adjusting the network architecture or increase the number of layers, adjust the learning rate or try different optimisers for these, you can also introduce some regularisation methods such as dropout to prevent overfitting.
2. For the prediction task of the Boston house price dataset, a linear regression model is used and the model error is evaluated, in order to get better model performance, other more complex models can be tried, such as decision trees, random forests or gradient boosting trees.
3. As for the fraud detection dataset, LightGBM was used to train the classifiers and output the evaluation metrics.


# Machine-learning(神经网络与Image Classification)
这个是机器学习的一些项目
内容包含了几个任务

任务1
使用自构建的网络对MNIST完成分类器训练

任务2
使用自构建的网络完成波士顿房价数据集（Sklearn内置数据）的预测任务.

任务3
第三个任务给到一个来自Texas A&M International University Dataverse的欺诈检测数据集。
该数据集本身内容已经过PCA降维，基本无法通过可视化方式去理解，因而我们用该数据进行纯神经网络的分类器训练。尝试将分类器精准度训练到70%以上。

Tips：
1。MNIST分类器这里如果想进一步提高准确率，可以考虑调整网络架构或增加层数，调整学习率或尝试不同的优化器这些，也可以引入一些正则化方法如dropout来防止过拟合。
2.对于波士顿房价数据集的预测任务，使用了线性回归模型并评估了模型误差,为了获得更好的模型性能，可以尝试其他更复杂的模型，比如决策树、随机森林或梯度提升树等.
3.至于欺诈检测数据集这里,是使用LightGBM进行了分类器的训练并输出了评价指标.
