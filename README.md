# 1111
训练：
1）	根据需求设置参数
2）	加载训练用的数据集
3）	通过torch下的DataLoader获取数据加载器
4）	定义优化器和损失函数
5）	循环在每个epoch下对模型进行训练

测试：
1）	参数设置同训练时设置的参数保持一致
2）	直接调用model（）并传入待测试图像进行测试
3）	通过numpy对数据进行展示
4）	通过pyplot进行可视化
