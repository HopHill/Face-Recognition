基于迁移学习方法的人脸识别
===
项目概述：
-----
人脸识别是近年来模式识别，图像处理，机器视觉，神经网络以及认知科学等领域研究的热点问题之一，并且在商业领域具有广泛的应用场景。人脸识别按照人脸信息的来源可以分为两类：基于静态人脸图像的识别和基于包含人脸的动态视频信息的识别。本项目以静态人脸图像识别作为研究目标，任务是通过一张带有人像的图像，对图像中的人脸进行识别并判断是谁。本项目采用的基准模型是卷积神经网络(CNN)，在此基础上，利用迁移学习的方法，采用预训练的[ResNet](https://arxiv.org/abs/1512.03385)、[FaceNet](https://arxiv.org/abs/1503.03832)模型作对比分析。

描述：
------
输入：一张彩色的人脸照片<br>
输出：照片的人名

数据集：
------
在这个人脸识别项目中，我们将使用一个开源数据集Five Celebrity Faces Dataset，这也是一个在Kaggle比赛中的一个数据集。我们也已经下载好了并放在./5-celebrity-faces-dataset中，数据集中包含五位名人的照片，Ben Affleck, Elton John, Jerry Seinfeld, Madonna, Mindy Kaling。文件下分train和val。

可选用工具：
------
[OpenCV](https://github.com/opencv/opencv)<br>
[OpenCV python tutorials](https://docs.opencv.org/3.1.0/d6/d00/tutorial_py_root.html)<br>
[tensorflow](https://github.com/tensorflow/tensorflow)<br>
[Keras](https://github.com/keras-team/keras)<br>
[Keras中文文档](https://keras.io/zh/) 

可选用模型：
------
可以尝试以下的模型，后面的数字代表年份和月份：

[VGGNet 14.09](https://arxiv.org/abs/1409.1556)<br>
[ResNet 15.12](https://arxiv.org/abs/1512.03385)<br>
[Inception v3 15.12](https://arxiv.org/abs/1512.00567)<br>
[InceptionResNetV2 16.02](https://arxiv.org/abs/1602.07261)<br>
[DenseNet 16.08](https://arxiv.org/abs/1608.06993)<br>
[Xception 16.10](https://arxiv.org/abs/1610.02357)<br>
[NASNet 17.07](https://arxiv.org/abs/1707.07012)<br>
参考 Keras 文档：[Documentation for individual models](https://keras.io/applications/#documentation-for-individual-models)

最低要求：
--------
本项目的最低要求是 kaggle Public Leaderboard 前10%。

