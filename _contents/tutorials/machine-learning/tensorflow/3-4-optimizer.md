---
youku_id: XMTYwMzk1NDM4OA
youtube_id: 9BmaWixFwj8
description: Tensorflow 中的optimizer 分了很多种,最基础的是 GradientDescentOptimizer,还有像 AdamOptimizer 等等.
author: 赵孔亚
chapter: 3
title: 优化器 optimizer
date: 2016-11-3
post-headings:
  - 各种不同的优化器
---
{% assign post-heading-count = -1 %}

学习资料:
  * 各种 Optimizer 的对比 [链接](http://cs231n.github.io/neural-networks-3/)(英文)
  * 机器学习-简介系列 [Optimizer]({% link _contents/tutorials/machine-learning/ML-intro/3-06-speed-up-learning.md %})
  * Tensorflow 的可用 optimizer [链接](https://www.tensorflow.org/versions/r0.9/api_docs/python/train.html)
  * 为 TF 2017 打造的[新版可视化教学代码](https://github.com/MorvanZhou/Tensorflow-Tutorial)

{% assign post-heading-count = post-heading-count | plus: 1 %}
<h4 class="tut-h4-pad" id="{{ page.post-headings[post-heading-count] }}">{{ page.post-headings[post-heading-count] }}</h4>

本次课程，我们会讲到`Tensorflow`里面的优化器。

Tensorflow 中的优化器会有很多不同的种类。最基本, 也是最常用的一种就是`GradientDescentOptimizer`。

在Google搜索中输入“tensorflow optimizer"可以看到`Tensorflow`提供了7种优化器：[链接](https://www.tensorflow.org/versions/r0.11/api_docs/python/train.html)

<img class="course-image" src="/static/results/tensorflow/3_4_1.png">

更多关系 Optimizer 的解释, 请参考我制作的 机器学习-简介系列 [Optimizer]({% link _contents/tutorials/machine-learning/ML-intro/3-06-speed-up-learning.md %})

