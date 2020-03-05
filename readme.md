# 基于卷积神经网络的纹理合成算法
这个算法是基于论文[Texture Synthesis Using Convolutional Neural Networks](https://arxiv.org/abs/1505.07376)的tensorflow（keras）实现，并在我Télécom Saint-Etienne三年级的综合学科项目中使用，导师提供的算法是基于caffe实现的，我重新将它迁移到了tensorflow架构下。

## 文件介绍
**original**：这个文件夹下包含了一些源纹理图像，可以用来做测试
**processed**：这个文件夹用于存储生成的图像
**utils.py**：这个python文件包含了预处理及后处理的简单算法以及计算VGG-16输出的主程序
**vgg_16.py**：这个python文件是VGG-16网络的构建，需要用到[vgg16.npy](https://mega.nz/#!YU1FWJrA!O1ywiCS2IiOlUCtCpI6HTJOMrneN-Qdv3ywQP5poecM)
**test.py**：是算法的主程序，使用时可以修改其中的输入输出路径以及height，weight参数调整输入输出的细节

