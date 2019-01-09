# 强烈推荐的TensorFlow、Pytorch和Keras的样例资源（深度学习初学者必须收藏）

**备注：github内容已经下载了**

**TensorFlow**、**Keras**和**Pytorch**是目前深度学习的主要框架，也是入门深度学习必须掌握的三大框架，但是官方文档相对内容较多，初学者往往无从下手。本人从github里搜到三个非常不错的学习资源，并对资源目录进行翻译，强烈建议初学者下载学习，这些资源包含了大量的代码示例（含数据集），个人认为，只要把以上资源运行一次，不懂的地方查官方文档，很快就能理解和运用这三大框架。

### 一、TensorFlow

**资源地址：**

https://github.com/aymericdamien/TensorFlow-Examples

**资源介绍：**

本资源旨在通过示例轻松深入了解TensorFlow。
为了便于阅读，它包括notebook和带注释的源代码。

它适合想要找到关于TensorFlow的清晰简洁示例的初学者。
除了传统的“原始”TensorFlow实现，您还可以找到最新的TensorFlow
API实践（例如layers,estimator,dataset, ......）。

最后更新（07/25/2018）：添加新示例（GBDT，Word2Vec）和 TF1.9兼容性！ （TF v1.9
+推荐）。

**配置环境：**

python 3.6以上，TensorFlow 1.8+

**资源目录：**

0  - 先决条件

-   机器学习简介

-   MNIST数据集简介

1  - 简介

-   Hello
    World(包含notebook和py源代码)。非常简单的例子，学习如何使用TensorFlow打印“hello
    world”。

-   基本操作(包含notebook和py源代码)。一个涵盖TensorFlow基本操作的简单示例。

-   TensorFlow Eager
    API基础知识(包含notebook和py源代码)。开始使用TensorFlow的Eager API。

2  - 基础模型

-   线性回归(包含notebook和py源代码)。使用TensorFlow实现线性回归。

-   线性回归（eager api）(包含notebook和py源代码)。使用TensorFlow的Eager
    API实现线性回归。

-   Logistic回归(包含notebook和py源代码)。使用TensorFlow实现Logistic回归。

-   Logistic回归（eager api）(包含notebook和py源代码)。使用TensorFlow的Eager
    API实现Logistic回归。

-   最近邻(包含notebook和py源代码)。使用TensorFlow实现最近邻算法。

-   K-Means(包含notebook和py源代码)。使用TensorFlow构建K-Means分类器。

-   随机森林(包含notebook和py源代码)。使用TensorFlow构建随机森林分类器。

-   Gradient Boosted Decision
    Tree（GBDT）(包含notebook和py源代码)。使用TensorFlow构建梯度提升决策树（GBDT）。

-   Word2Vec（词嵌入）(包含notebook和py源代码)。使用TensorFlow从Wikipedia数据构建词嵌入模型（Word2Vec）。

3  - 神经网络

-   **监督学习部分**

-   简单神经网络(包含notebook和py源代码)。构建一个简单的神经网络（如多层感知器）来对MNIST数字数据集进行分类。
    Raw TensorFlow实现。

-   简单神经网络（tf.layers / estimator
    api）(包含notebook和py源代码)。使用TensorFlow'layers'和'estimator'API构建一个简单的神经网络（如：Multi-layer
    Perceptron）来对MNIST数字数据集进行分类。

-   简单神经网络（Eager API）(包含notebook和py源代码)。使用TensorFlow Eager
    API构建一个简单的神经网络（如多层感知器）来对MNIST数字数据集进行分类。

-   卷积神经网络(包含notebook和py源代码)。构建卷积神经网络以对MNIST数字数据集进行分类。
    Raw TensorFlow实现。

-   卷积神经网络（tf.layers / estimator
    api）(包含notebook和py源代码)。使用TensorFlow'layers'和'estimator'API构建卷积神经网络，对MNIST数字数据集进行分类。

-   递归神经网络（LSTM）(包含notebook和py源代码)。构建递归神经网络（LSTM）以对MNIST数字数据集进行分类。

-   双向LSTM(包含notebook和py源代码)。构建双向递归神经网络（LSTM）以对MNIST数字数据集进行分类。

-   动态LSTM(包含notebook和py源代码)。构建一个递归神经网络（LSTM），执行动态计算以对不同长度的序列进行分类。

-   **无监督**

-   自动编码器(包含notebook和py源代码)。构建自动编码器以将图像编码为较低维度并重新构建它。

-   变分自动编码器（(包含notebook和py源代码)。构建变分自动编码器（VAE），对噪声进行编码和生成图像。

-   GAN（Generative Adversarial
    Networks）(包含notebook和py源代码)。构建生成对抗网络（GAN）以从噪声生成图像。

-   DCGAN（Deep Convolutional Generative Adversarial
    Networks）(包含notebook和py源代码)。构建深度卷积生成对抗网络（DCGAN）以从噪声生成图像。

4  - 工具

-   保存和还原模型(包含notebook和py源代码)。使用TensorFlow保存和还原模型。

-   Tensorboard  -
    图形和损失可视化(包含notebook和py源代码)。使用Tensorboard可视化计算图并绘制损失。

-   Tensorboard  -
    高级可视化(包含notebook和py源代码)。深入了解Tensorboard;可视化变量，梯度等......

5  - 数据管理

-   构建图像数据集(包含notebook和py源代码)。使用TensorFlow数据队列，从图像文件夹或数据集文件构建您自己的图像数据集。

-   TensorFlow数据集API(包含notebook和py源代码)。引入TensorFlow数据集API以优化输入数据管道。

6  - 多GPU

-   多GPU的基本操作(包含notebook和py源代码)。在TensorFlow中引入多GPU的简单示例。

-   在多GPU上训练神经网络(包含notebook和py源代码)。一个清晰简单的TensorFlow实现，用于在多个GPU上训练卷积神经网络。

数据集

-   一些示例需要MNIST数据集进行训练和测试。官方网站：http://yann.lecun.com/exdb/mnist/

### 二、Keras

**资源地址：**

https://github.com/erhwenkuo/deep-learning-with-keras-notebooks

**资源介绍：**

这个github的repository主要是**ErhWen
Kuo**在学习Keras的一些记录及练习。希望在学习过程中发现到一些好的信息与示例也可以对想要学习使用Keras来解决问题的同学带来帮助。这些notebooks主要是使用Python
3.6与Keras 2.1.1版本跑在一台配置Nivida 1080Ti的Windows
10的机台所产生的结果，但有些部份会参杂一些Tensorflow与其它的函式库的介绍。

**配置环境：**

python 3.6以上，Keras 2.1.1

**资源目录：**

0.图象数据集/工具介绍

-   0.0: COCO API解说与简单示例

-   0.1:土炮自制扑克牌图象数据集

-   0.2:使用Pillow来进行图像处理

1.Keras API示例

-   1.0:使用图像增强来进行深度学习

-   1.1:如何使用Keras函数式API进行深度学习

-   1.2:从零开始构建VGG网络来学习Keras

-   1.3:使用预训练的模型来分类照片中的物体

-   1.4:使用图像增强来训练小数据集

-   1.5:使用预先训练的卷积网络模型

-   1.6:卷积网络模型学习到什么的可视化

-   1.7:构建自动编码器（Autoencoder）

-   1.8:序列到序列（Seq-to-Seq）学习介绍

-   1.9: One-hot编码工具程序介绍

-   1.10:循环神经网络（RNN）介绍

-   1.11: LSTM的返回序列和返回状态之间的区别

-   1.12:用LSTM来学习英文字母表顺序

2.图像分类（Image Classification）

-   2.0: Julia（Chars74K）字母图像分类

-   2.1:交通标志图像分类

-   2.2:辛普森卡通图像角色分类

-   2.3:时尚服饰图像分类

-   2.4:人脸关键点辨识

-   2.5: Captcha验证码分类

-   2.6: Mnist手写图像分类（MLP）

-   2.7: Mnist手写图像分类（CNN）

3.目标检测（Object Recognition）

-   3.0: YOLO目标检测算法概念与介绍

-   3.1: YOLOv2目标检测示例

-   3.2:浣熊（Racoon）检测-YOLOv2模型训练与调整

-   3.3:浣熊（Racoon）检测-YOLOv2模型的使用

-   3.4:袋鼠（Kangaroo）检测-YOLOv2模型训练与调整

-   3.5:双手（Hands）检测-YOLOv2模型训练与调整

-   3.6:辛普森卡通图象角色（Simpson）检测-YOLOv2模型训练与调整

-   3.7: MS COCO图象检测-YOLOv2模型训练与调整

4.物体分割（Object Segmentation）

5.关键点检测（Keypoint Detection）

6.图象标题（Image Caption）

7.人脸检测识别（Face Detection/Recognition）

-   7.0:人脸检测- OpenCV（Haar特征分类器）

-   7.1:人脸检测- MTCNN（Multi-task Cascaded Convolutional Networks）

-   7.2:人脸识别-脸部检测、对齐&裁剪

-   7.3:人脸识别-人脸部特征提取&人脸分类器

-   7.4:人脸识别-转换、对齐、裁剪、特征提取与比对

-   7.5:脸部关键点检测（dlib）

-   7.6:头部姿态（Head pose）估计（dlib）

8.自然语言处理（Natural Language Processing）

-   8.0:词嵌入（word embeddings）介绍

-   8.1:使用结巴（jieba）进行中文分词

-   8.2: Word2vec词嵌入（word embeddings）的基本概念

-   8.3:使用结巴（jieba）进行歌词分析

-   8.4:使用gensim训练中文词向量（word2vec）

### 三、Pytorch

**资源地址：**

https://github.com/yunjey/pytorch-tutorial

**资源介绍：**

这个资源为深度学习研究人员提供了学习PyTorch的教程代码大多数模型都使用少于30行代码实现。
在开始本教程之前，建议先看完Pytorch官方教程。

**配置环境：**

python 2.7或者3.5以上，pytorch 0.4

**资源目录：**

1.基础知识

-   PyTorch基础知识

-   线性回归

-   Logistic回归

-   前馈神经网络

2.中级

-   卷积神经网络

-   深度残差网络

-   递归神经网络

-   双向递归神经网络

-   语言模型（RNN-LM）

3.高级

-   生成性对抗网络

-   变分自动编码器

-   神经风格转移

-   图像字幕（CNN-RNN）

4.工具

-   PyTorch中的TensorBoard

 总结

>   **TensorFlow**、**Keras**和**Pytorch**是目前深度学习的主要框架，也是入门深度学习必须掌握的三大框架，但是官方文档相对内容较多，初学者往往无从下手。本人从github里搜到三个非常不错的学习资源，并对资源目录进行翻译，强烈建议初学者下载学习，这些资源包含了大量的代码示例（含数据集），个人认为，只要把以上资源运行一次，不懂的地方查官方文档，很快就能理解和运用这三大框架。



![C:\\Users\\being\\AppData\\Local\\Temp\\1546479942(1).jpg](media/8350a0b0f82151ca74d8d37374749127.png)

**机器学习初学者**

**QQ群：554839127**

**（注意：本站有6个qq群，加入过任何一个的不需要再加）**
