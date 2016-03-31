---
layout: post
title: "机器学习：神经网络与梯度下降=>反向传导算法"
description: ""
category:
tags: [MachineLearning]
---
{% include JB/setup %}

### Machine Learning: Neural Network and Gradient descent => backpropagation algorithm

看了很多资料。。终于找到点感觉。原来梯度下降是能用在神经网络上的，这样就make sense了。原本只看神经网络的时候发现神经网络没提到如何调整参数，不知道怎么用有标签的数据进行有监督训练。现在了解到，反向传导算法(BP)，就是先随机神经元中的参数组，然后输入，算一个结果出来，然后再用已有的结果来对比算出来的结果，用比如梯度下降法调整参数，然后迭代，反向传导，修改之前隐层中的参数，从而达到训练的目的(从后向前求导，求导的链式法则)。

链接:http://deeplearning.stanford.edu/wiki/index.php/%E5%8F%8D%E5%90%91%E4%BC%A0%E5%AF%BC%E7%AE%97%E6%B3%95
