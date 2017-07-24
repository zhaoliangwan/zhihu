# 说明

## 简介

该Repo内容为知乎专栏《机器不学习》的源代码。

专栏地址：<https://zhuanlan.zhihu.com/zhaoyeyu>

## 代码框架
```TensorFlow```

## 包含内容

- ```anna_lstm```: 基于RNN（LSTM）对《安娜卡列尼娜》英文文本的学习，实现一个字符级别的生成器。 
> 文章地址：[《安娜卡列尼娜》文本生成——利用TensorFlow构建LSTM模型
](https://zhuanlan.zhihu.com/p/27087310)


- ```skip-gram```: 实现skip-gram算法的Word2Vec，基于对英文语料的训练，模型学的各个单词的嵌入向量。
> 文章地址：[基于TensorFlow实现Skip-Gram模型](https://zhuanlan.zhihu.com/p/27296712)


- ```generate_lyrics```: 基于RNN实现歌词生成器。


- ```basic_seq2seq```: 基于RNN Encoder-Decoder结构的Seq2Seq模型，实现对一个单词中字母的排序。
> 文章地址：[从Encoder到Decoder实现Seq2Seq模型](https://zhuanlan.zhihu.com/p/27608348)


- ```denoise_auto_encoder```: 基于MNIST手写数据集训练了一个自编码器，并在此基础上增加卷积层实现一个卷积自编码器，从而实现对图像的降噪。
> 文章地址：[利用卷积自编码器对图片进行降噪](https://zhuanlan.zhihu.com/p/27902193)


- ```cifar-cnn```: 对Kaggle上CIFAR图像分类比赛的一个实现，分别对比了KNN和卷积神经网络在数据上的表现效果。
> 文章地址：[利用卷积神经网络处理CIFAR图像分类](https://zhuanlan.zhihu.com/p/28035475)
![](https://raw.githubusercontent.com/NELSONZHAO/zhihu/master/cifar_cnn/example_pic.png)


- ```mnist_gan```: 基于MNIST手写数据集，训练了一个隐层为Leaky ReLU的生成对抗网络，让模型学会自己生成手写数字。
> 文章地址：[生成对抗网络（GAN）之MNIST数据生成](https://zhuanlan.zhihu.com/p/28057434)
![](https://raw.githubusercontent.com/NELSONZHAO/zhihu/master/mnist_gan/gan_examples.png)

## 备注
不定期更新干货，欢迎Star，欢迎Fork。