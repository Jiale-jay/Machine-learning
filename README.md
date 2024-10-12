# djjadd
这个是机器学习的一些项目
内容包含了几个任务

1.掌握Python和TF2.x的基本使用方法。
Deep Learning
（推荐）http://www.ai-start.com/dl2017/
https://github.com/Mikoto10032/DeepLearning
Tensorflow 2.x
（推荐）https://tf.wiki/zh_hans/
https://www.tensorflow.org/tutorials

任务1
使用自构建的网络对MNIST完成分类器训练

任务2
使用自构建的网络完成波士顿房价数据集（Sklearn内置数据）的预测任务，可以参考：
https://www.paddlepaddle.org.cn/tutorials/projectdetail/3907095#anchor-20

任务3
第三个任务给到一个来自Texas A&M International University Dataverse的欺诈检测数据集。
https://doi.org/10.18738/T8/M7NKGO
该数据集本身内容已经过PCA降维，基本无法通过可视化方式去理解，因而我们用该数据进行纯神经网络的分类器训练。尝试将你的分类器精准度训练到70%以上。

Tips：
1。MNIST分类器这里如果想进一步提高准确率，可以考虑调整网络架构或增加层数，调整学习率或尝试不同的优化器这些，也可以引入一些正则化方法如dropout来防止过拟合。
2.对于波士顿房价数据集的预测任务，使用了线性回归模型并评估了模型误差,为了获得更好的模型性能，可以尝试其他更复杂的模型，比如决策树、随机森林或梯度提升树等.
3.至于欺诈检测数据集这里,是使用LightGBM进行了分类器的训练并输出了评价指标.
